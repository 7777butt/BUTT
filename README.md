<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ATHLETIC PRO | Premium Sportswear</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }
        
        body {
            background-color: #fff;
            color: #000;
        }
        
        /* Header Styles */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 5%;
            position: sticky;
            top: 0;
            background: white;
            z-index: 100;
            border-bottom: 1px solid #e5e5e5;
        }
        
        .logo {
            font-size: 24px;
            font-weight: 700;
            letter-spacing: -1px;
        }
        
        .logo span {
            color: #cc0000;
        }
        
        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }
        
        nav a {
            text-decoration: none;
            color: #000;
            font-weight: 500;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .header-icons {
            display: flex;
            gap: 20px;
        }
        
        .header-icons a {
            text-decoration: none;
            color: #000;
            font-size: 18px;
        }
        
        /* Hero Section */
        .hero {
            height: 80vh;
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1542291026-7eec264c27ff?ixlib=rb-4.0.3') center/cover no-repeat;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }
        
        .hero h1 {
            font-size: 60px;
            font-weight: 900;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: -2px;
        }
        
        .hero p {
            font-size: 20px;
            max-width: 600px;
            margin-bottom: 30px;
            font-weight: 300;
        }
        
        .cta-button {
            background: #cc0000;
            color: white;
            padding: 15px 40px;
            text-decoration: none;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: all 0.3s ease;
        }
        
        .cta-button:hover {
            background: #000;
        }
        
        /* Products Section */
        .products {
            padding: 80px 5%;
            text-align: center;
        }
        
        .section-title {
            font-size: 36px;
            font-weight: 900;
            margin-bottom: 50px;
            text-transform: uppercase;
            letter-spacing: -1px;
        }
        
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
            margin-top: 40px;
        }
        
        .product-card {
            position: relative;
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        
        .product-card:hover {
            transform: translateY(-10px);
        }
        
        .product-image {
            width: 100%;
            height: 300px;
            object-fit: cover;
            display: block;
        }
        
        .product-info {
            padding: 20px 0;
        }
        
        .product-name {
            font-size: 18px;
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        .product-price {
            font-size: 16px;
            color: #cc0000;
            font-weight: 700;
        }
        
        /* Footer */
        footer {
            background: #000;
            color: white;
            padding: 60px 5% 30px;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .footer-column h3 {
            font-size: 16px;
            font-weight: 700;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .footer-column ul {
            list-style: none;
        }
        
        .footer-column li {
            margin-bottom: 12px;
        }
        
        .footer-column a {
            color: #ccc;
            text-decoration: none;
            font-size: 14px;
            transition: color 0.3s ease;
        }
        
        .footer-column a:hover {
            color: white;
        }
        
        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid #333;
            color: #666;
            font-size: 14px;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 40px;
            }
            
            nav ul {
                display: none;
            }
            
            .mobile-menu {
                display: block;
                font-size: 24px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">ATHLETIC<span>PRO</span></div>
        <nav>
            <ul>
                <li><a href="#">Men</a></li>
                <li><a href="#">Women</a></li>
                <li><a href="#">Kids</a></li>
                <li><a href="#">Sale</a></li>
            </ul>
        </nav>
        <div class="header-icons">
            <a href="#" title="Search">🔍</a>
            <a href="#" title="Account">👤</a>
            <a href="#" title="Cart">🛒</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>JUST DO IT</h1>
        <p>Discover the latest innovations in athletic performance and style</p>
        <a href="#" class="cta-button">Shop Now</a>
    </section>

    <!-- Products Section -->
    <section class="products">
        <h2 class="section-title">Featured Products</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1549298916-b41d501d3772?ixlib=rb-4.0.3&auto=format&fit=crop&w=600" alt="Running Shoes" class="product-image">
                <div class="product-info">
                    <div class="product-name">UltraRun Pro</div>
                    <div class="product-price">$129.99</div>
                </div>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1525966222134-fcfa99b8ae77?ixlib=rb-4.0.3&auto=format&fit=crop&w=600" alt="Training Shoes" class="product-image">
                <div class="product-info">
                    <div class="product-name">FlexTrain Elite</div>
                    <div class="product-price">$99.99</div>
                </div>
            </div>
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?ixlib=rb-4.0.3&auto=format&fit=crop&w=600" alt="Basketball Shoes" class="product-image">
                <div class="product-info">
                    <div class="product-name">AirCourt Max</div>
                    <div class="product-price">$149.99</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-column">
                <h3>Shop</h3>
                <ul>
                    <li><a href="#">Men</a></li>
                    <li><a href="#">Women</a></li>
                    <li><a href="#">Kids</a></li>
                    <li><a href="#">New Arrivals</a></li>
                    <li><a href="#">Sale</a></li>
                </ul>
            </div>
            <div class="footer-column">
                <h3>Help</h3>
                <ul>
                    <li><a href="#">Order Status</a></li>
                    <li><a href="#">Shipping & Returns</a></li>
                    <li><a href="#">Size Guide</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div class="footer-column">
                <h3>About</h3>
                <ul>
                    <li><a href="#">Our Story</a></li>
                    <li><a href="#">Sustainability</a></li>
                    <li><a href="#">Careers</a></li>
                    <li><a href="#">Press</a></li>
                </ul>
            </div>
            <div class="footer-column">
                <h3>Connect</h3>
                <ul>
                    <li><a href="#">Instagram</a></li>
                    <li><a href="#">Twitter</a></li>
                    <li><a href="#">Facebook</a></li>
                    <li><a href="#">YouTube</a></li>
                </ul>
            </div>
        </div>
        <div class="copyright">
            &copy; 2023 AthleticPro. All rights reserved.
        </div>
    </footer>
</body>
</html>
