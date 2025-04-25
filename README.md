<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KS STORE - Premium Products</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <h1>KS STORE</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="cart-icon">
                <i class="fas fa-shopping-cart"></i>
                <span class="cart-count">0</span>
            </div>
        </div>
    </header>

    <section class="hero" id="home">
        <div class="container">
            <h2>Premium Quality Products</h2>
            <p>Discover our exclusive collection at KS STORE</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
    </section>

    <section class="products" id="products">
        <div class="container">
            <h2>Our Products</h2>
            <div class="product-grid">
                <!-- Product 1 -->
                <div class="product-card">
                    <img src="product1.jpg" alt="Product 1">
                    <h3>Product Name 1</h3>
                    <p class="price">$29.99</p>
                    <button class="add-to-cart" data-id="1">Add to Cart</button>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card">
                    <img src="product2.jpg" alt="Product 2">
                    <h3>Product Name 2</h3>
                    <p class="price">$39.99</p>
                    <button class="add-to-cart" data-id="2">Add to Cart</button>
                </div>
                
                <!-- Add more products as needed -->
            </div>
        </div>
    </section>

    <section class="about" id="about">
        <div class="container">
            <h2>About KS STORE</h2>
            <p>Welcome to KS STORE, your premier destination for high-quality products. We pride ourselves on offering exceptional value and customer service.</p>
            <p>Founded in 2023, KS STORE has quickly become a trusted name in the industry, serving thousands of satisfied customers worldwide.</p>
        </div>
    </section>

    <section class="contact" id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 KS STORE. All rights reserved.</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </footer>

    <!-- Shopping Cart Modal -->
    <div class="cart-modal">
        <div class="cart-content">
            <span class="close-cart">&times;</span>
            <h2>Your Shopping Cart</h2>
            <div class="cart-items">
                <!-- Cart items will be added here dynamically -->
            </div>
            <div class="cart-total">
                <p>Total: $<span id="total-amount">0.00</span></p>
                <button class="checkout-btn">Proceed to Checkout</button>
            </div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
