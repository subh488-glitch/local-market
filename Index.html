<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Local Market - Online Shopping Website</title>
    <style>
        /* === General Styling === */
        :root {
            --primary-color: #2e7d32;
            --primary-hover: #1b5e20;
            --secondary-color: #4caf50;
            --bg-light: #f4f9f4;
            --text-dark: #333;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        html {
            scroll-behavior: smooth;
        }

        /* === Navigation Bar === */
        .navbar {
            background-color: var(--primary-color);
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo {
            margin: 0;
            font-size: 24px;
        }

        .nav-links {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
            gap: 20px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            transition: opacity 0.3s;
            cursor: pointer;
        }

        .nav-links a:hover {
            opacity: 0.8;
            text-decoration: underline;
        }

        /* === Buttons === */
        .btn {
            background-color: var(--primary-color);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: var(--primary-hover);
        }

        /* === Home / Hero Section === */
        .hero-section {
            background-color: #e8f5e9;
            text-align: center;
            padding: 80px 20px;
            border-bottom: 2px solid #c8e6c9;
        }

        .hero-content h2 {
            font-size: 36px;
            color: var(--primary-hover);
            margin-bottom: 10px;
        }

        .hero-content p {
            font-size: 18px;
            margin-bottom: 30px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        /* === Page Sections === */
        .section {
            padding: 50px 20px;
            max-width: 1100px;
            margin: 0 auto;
        }

        .alt-bg {
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .section-title {
            text-align: center;
            color: var(--primary-color);
            margin-bottom: 40px;
            font-size: 28px;
        }

        /* === Products Section === */
        .product-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 25px;
        }

        .product-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 220px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 6px;
            background-color: #eee; 
        }

        .product-card h3 {
            font-size: 18px;
            margin: 15px 0 5px;
        }

        .price {
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 15px;
            font-size: 18px;
        }

        .btn-container button {
            background-color: var(--secondary-color);
            color: white;
            border: none;
            padding: 10px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            font-size: 15px;
            font-weight: bold;
        }

        .btn-container button:hover {
            background-color: var(--primary-color);
        }

        /* Quantity Controls inside Product Card */
        .qty-controls {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #e8f5e9;
            border-radius: 4px;
            padding: 5px;
        }

        .qty-controls button {
            width: 35px !important;
            padding: 5px !important;
            background-color: var(--primary-color) !important;
        }

        .qty-controls span {
            font-weight: bold;
            font-size: 16px;
            color: var(--primary-hover);
        }

        /* === Floating Cart Button === */
        .floating-cart {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background-color: var(--primary-color);
            color: white;
            padding: 15px 25px;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            z-index: 999;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: transform 0.2s, background-color 0.3s;
        }

        .floating-cart:hover {
            background-color: var(--primary-hover);
            transform: scale(1.05);
        }

        /* === Cart Modal === */
        .cart-modal {
            display: none;
            position: fixed;
            z-index: 1001;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.6);
        }

        .cart-modal-content {
            background-color: white;
            margin: 5% auto;
            padding: 30px;
            width: 90%;
            max-width: 600px;
            border-radius: 8px;
            position: relative;
            max-height: 80vh;
            overflow-y: auto;
        }

        .close-modal {
            position: absolute;
            right: 20px;
            top: 15px;
            font-size: 28px;
            font-weight: bold;
            color: #777;
            cursor: pointer;
        }

        .close-modal:hover {
            color: #000;
        }

        .cart-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #eee;
            padding: 15px 0;
        }

        .cart-item-info {
            font-size: 16px;
            flex-grow: 1;
        }

        .modal-qty-controls {
            display: flex;
            align-items: center;
            gap: 10px;
            margin: 0 15px;
        }

        .modal-qty-controls button {
            background-color: #ddd;
            border: none;
            padding: 5px 10px;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
        }
        
        .modal-qty-controls button:hover {
            background-color: #ccc;
        }

        .remove-btn {
            background-color: #d32f2f;
            color: white;
            border: none;
            padding: 6px 12px;
            border-radius: 4px;
            cursor: pointer;
        }

        .remove-btn:hover {
            background-color: #b71c1c;
        }

        .cart-total {
            margin-top: 20px;
            text-align: right;
            font-size: 22px;
            border-top: 2px solid var(--primary-color);
            padding-top: 20px;
        }

        .checkout-btn {
            margin-top: 15px;
            font-size: 18px;
            padding: 12px 25px;
            width: 100%;
        }

        /* === Toast Notification === */
        .toast {
            visibility: hidden;
            min-width: 250px;
            background-color: var(--primary-color);
            color: #fff;
            text-align: center;
            border-radius: 4px;
            padding: 16px;
            position: fixed;
            z-index: 2000;
            left: 50%;
            top: 30px;
            transform: translateX(-50%);
            font-size: 16px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            transition: opacity 0.5s, top 0.5s;
            opacity: 0;
        }

        .toast.show {
            visibility: visible;
            opacity: 1;
            top: 50px;
        }

        /* === About & Contact Sections === */
        .about-content {
            text-align: center;
            font-size: 17px;
            max-width: 800px;
            margin: 0 auto;
        }

        .contact-form {
            max-width: 500px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .contact-form label {
            margin-top: 15px;
            font-weight: bold;
            color: var(--primary-hover);
        }

        .contact-form input,
        .contact-form textarea {
            padding: 10px;
            margin-top: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 15px;
            font-family: inherit;
        }

        .contact-form button {
            margin-top: 25px;
        }

        /* === Footer === */
        footer {
            background-color: var(--primary-hover);
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
            font-size: 15px;
        }

        /* === Checkout & Confirmation Views === */
        .full-page-view {
            display: none;
            min-height: 80vh;
            padding: 50px 20px;
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
        }

        .payment-options {
            text-align: left;
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 30px auto;
            max-width: 400px;
        }

        .payment-options label {
            display: block;
            margin: 15px 0;
            font-size: 18px;
            cursor: pointer;
        }

        /* New Payment Details Styling */
        .payment-details {
            display: none;
            margin-top: 15px;
            padding: 15px;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        .pay-input {
            width: 100%;
            padding: 10px;
            margin-top: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
            font-size: 15px;
        }

        .success-icon {
            font-size: 80px;
            color: var(--primary-color);
            margin-bottom: 20px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .nav-links {
                flex-wrap: wrap;
                justify-content: center;
                gap: 10px;
            }
            .navbar {
                flex-direction: column;
                gap: 15px;
            }
        }
    </style>
</head>
<body>

    <!-- Main Store View Wrapper -->
    <div id="main-store-view">
        <!-- Navigation Bar -->
        <nav class="navbar">
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a onclick="openCartModal()">Cart (<span id="nav-cart-count">0</span>)</a></li>
        </ul>
    </nav>

    <!-- Custom Toast Notification -->
    <div id="toast" class="toast">Message Here</div>

    <!-- Floating Cart Button -->
    <div class="floating-cart" onclick="openCartModal()">
        🛒 View Cart (<span id="float-cart-count">0</span>)
    </div>

    <!-- Cart Modal Overlay -->
    <div id="cart-modal" class="cart-modal">
        <div class="cart-modal-content">
            <span class="close-modal" onclick="closeCartModal()">&times;</span>
            <h2 style="color: #2e7d32; margin-top: 0;">Your Shopping Cart</h2>
            
            <div id="cart-items-container">
                <p style="text-align: center; color: #777;">Your cart is empty.</p>
            </div>
            
            <div class="cart-total">
                <h3>Total Amount: ₹<span id="cart-total-price">0</span></h3>
                <button class="btn checkout-btn" onclick="checkout()">Proceed to Checkout</button>
            </div>
        </div>
    </div>

    <!-- Home Section -->
    <section id="home" class="hero-section">
        <div class="hero-content">
            <h2>Welcome to Local Market</h2>
            <p>Buy fresh groceries, fruits, vegetables, and daily essentials from your nearby local store easily! Quality products delivered with care.</p>
            <a href="#products" class="btn">Start Shopping</a>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="section">
        <h2 class="section-title">Our Daily Products</h2>
        <div class="product-grid">
            
            <!-- Product 1 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1560806887-1e4cd0b6cbd6?w=300" alt="Apples" onerror="this.src='https://placehold.co/300x200/eee/333?text=Apples'">
                <h3>Fresh Apples</h3>
                <p class="price">₹120 / kg</p>
                <div class="btn-container" id="btn-p1" data-name="Fresh Apples" data-price="120">
                    <!-- Button content will be injected by JS -->
                </div>
            </div>

            <!-- Product 2 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1571771894821-ce9b6c11b08e?w=300" alt="Bananas" onerror="this.src='https://placehold.co/300x200/eee/333?text=Bananas'">
                <h3>Ripe Bananas</h3>
                <p class="price">₹50 / dozen</p>
                <div class="btn-container" id="btn-p2" data-name="Ripe Bananas" data-price="50"></div>
            </div>

            <!-- Product 3 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1592924357228-91a4daadcfea?w=300" alt="Tomatoes" onerror="this.src='https://placehold.co/300x200/eee/333?text=Tomatoes'">
                <h3>Fresh Tomatoes</h3>
                <p class="price">₹40 / kg</p>
                <div class="btn-container" id="btn-p3" data-name="Fresh Tomatoes" data-price="40"></div>
            </div>

            <!-- Product 4 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1518977676601-b53f82aba655?w=300" alt="Potatoes" onerror="this.src='https://placehold.co/300x200/eee/333?text=Potatoes'">
                <h3>Potatoes</h3>
                <p class="price">₹30 / kg</p>
                <div class="btn-container" id="btn-p4" data-name="Potatoes" data-price="30"></div>
            </div>

            <!-- Product 5 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1563636619-e9143da7973b?w=300" alt="Milk" onerror="this.src='https://placehold.co/300x200/eee/333?text=Milk'">
                <h3>Fresh Milk</h3>
                <p class="price">₹60 / liter</p>
                <div class="btn-container" id="btn-p5" data-name="Fresh Milk" data-price="60"></div>
            </div>

            <!-- Product 6 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff?w=300" alt="Bread" onerror="this.src='https://placehold.co/300x200/eee/333?text=Bread'">
                <h3>Brown Bread</h3>
                <p class="price">₹45 / pack</p>
                <div class="btn-container" id="btn-p6" data-name="Brown Bread" data-price="45"></div>
            </div>

            <!-- Product 7 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1586201375761-83865001e31c?w=300" alt="Rice" onerror="this.src='https://placehold.co/300x200/eee/333?text=Rice'">
                <h3>Basmati Rice</h3>
                <p class="price">₹90 / kg</p>
                <div class="btn-container" id="btn-p7" data-name="Basmati Rice" data-price="90"></div>
            </div>

            <!-- Product 8 -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1558961363-fa8fdf82db35?w=300" alt="Biscuits" onerror="this.src='https://placehold.co/300x200/eee/333?text=Biscuits'">
                <h3>Butter Biscuits</h3>
                <p class="price">₹25 / pack</p>
                <div class="btn-container" id="btn-p8" data-name="Butter Biscuits" data-price="25"></div>
            </div>

            <!-- Additional Products -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1576045057995-568f588f82fb?w=300" alt="Spinach" onerror="this.src='https://placehold.co/300x200/eee/333?text=Spinach'">
                <h3>Fresh Spinach</h3>
                <p class="price">₹20 / bunch</p>
                <div class="btn-container" id="btn-p9" data-name="Fresh Spinach" data-price="20"></div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1618512496248-a07fe83aa8cb?w=300" alt="Onions" onerror="this.src='https://placehold.co/300x200/eee/333?text=Onions'">
                <h3>Red Onions</h3>
                <p class="price">₹35 / kg</p>
                <div class="btn-container" id="btn-p10" data-name="Red Onions" data-price="35"></div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1553279768-865429fa0078?w=300" alt="Mangoes" onerror="this.src='https://placehold.co/300x200/eee/333?text=Mangoes'">
                <h3>Sweet Mangoes</h3>
                <p class="price">₹150 / kg</p>
                <div class="btn-container" id="btn-p11" data-name="Sweet Mangoes" data-price="150"></div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1537640538966-79f369143f8f?w=300" alt="Grapes" onerror="this.src='https://placehold.co/300x200/eee/333?text=Grapes'">
                <h3>Green Grapes</h3>
                <p class="price">₹80 / kg</p>
                <div class="btn-container" id="btn-p12" data-name="Green Grapes" data-price="80"></div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1582722872445-44dc5f7e3c8f?w=300" alt="Eggs" onerror="this.src='https://placehold.co/300x200/eee/333?text=Eggs'">
                <h3>Farm Eggs</h3>
                <p class="price">₹85 / dozen</p>
                <div class="btn-container" id="btn-p13" data-name="Farm Eggs" data-price="85"></div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1588195538326-c5b1e9f80a1b?w=300" alt="Butter" onerror="this.src='https://placehold.co/300x200/eee/333?text=Butter'">
                <h3>Fresh Butter</h3>
                <p class="price">₹55 / 100g</p>
                <div class="btn-container" id="btn-p14" data-name="Fresh Butter" data-price="55"></div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1585996887550-98311ab812f8?w=300" alt="Dal" onerror="this.src='https://placehold.co/300x200/eee/333?text=Toor+Dal'">
                <h3>Toor Dal</h3>
                <p class="price">₹140 / kg</p>
                <div class="btn-container" id="btn-p15" data-name="Toor Dal" data-price="140"></div>
            </div>

            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1581441363689-1f3c3c414635?w=300" alt="Sugar" onerror="this.src='https://placehold.co/300x200/eee/333?text=Sugar'">
                <h3>White Sugar</h3>
                <p class="price">₹45 / kg</p>
                <div class="btn-container" id="btn-p16" data-name="White Sugar" data-price="45"></div>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section alt-bg">
        <h2 class="section-title">About Local Market</h2>
        <div class="about-content">
            <p>Local Market is a small web application created to help customers easily purchase daily-use products like groceries, vegetables, and household items from nearby local shops online.</p>
            <p>Our aim is to bring small local vendors closer to everyday consumers using basic digital tools. This platform allows you to browse items, adjust quantities, and place mock orders seamlessly.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2 class="section-title">Contact Us</h2>
        <form class="contact-form" onsubmit="handleContactSubmit(event)">
            <label for="name">Name:</label>
            <input type="text" id="name" required placeholder="Enter your name">

            <label for="email">Email:</label>
            <input type="email" id="email" required placeholder="Enter your email">

            <label for="message">Message:</label>
            <textarea id="message" rows="5" required placeholder="Write your message here..."></textarea>

            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p><strong>Local Market</strong> &copy; 2026. All rights reserved.</p>
        <p>Made as a college project for BTech Computer Science (1st Year).</p>
    </footer>
    </div> <!-- End of main-store-view -->

    <!-- Checkout View -->
    <div id="checkout-view" class="full-page-view">
        <h2 class="section-title">Checkout</h2>
        <h3>Total Amount to Pay: ₹<span id="checkout-total-price">0</span></h3>
        
        <div class="payment-options">
            <h4 style="margin-top:0; color: #2e7d32;">Select Payment Method:</h4>
            <label>
                <input type="radio" name="payment" value="cod" checked onchange="togglePaymentDetails()"> Cash on Delivery (COD)
            </label>
            <label>
                <input type="radio" name="payment" value="upi" onchange="togglePaymentDetails()"> UPI (GPay, PhonePe, etc.)
            </label>
            <label>
                <input type="radio" name="payment" value="card" onchange="togglePaymentDetails()"> Credit / Debit Card
            </label>

            <!-- Dynamic Payment Containers -->
            <div id="cod-details" class="payment-details" style="display: block;">
                <p style="color: #2e7d32; font-size: 18px;"><strong>Amount to be paid on delivery: ₹<span id="cod-amount">0</span></strong></p>
            </div>

            <div id="upi-details" class="payment-details" style="text-align: center;">
                <p>Scan the QR Code below to pay <strong>₹<span id="upi-amount">0</span></strong></p>
                <img src="https://placehold.co/150x150/eee/333?text=Dummy+QR" alt="UPI QR Code" style="margin: 10px 0; border: 2px solid #ccc; padding: 5px;">
            </div>

            <div id="card-details" class="payment-details">
                <input type="text" placeholder="Card Number (e.g. 1234 5678 9101 1121)" class="pay-input">
                <div style="display: flex; gap: 10px;">
                    <input type="text" placeholder="MM/YY" class="pay-input" style="width: 50%;">
                    <input type="text" placeholder="CVV" class="pay-input" style="width: 50%;">
                </div>
                <input type="text" placeholder="Name on Card" class="pay-input">
            </div>
        </div>

        <button class="btn" style="font-size: 18px; padding: 12px 30px;" onclick="confirmOrder()">Confirm Order & Pay</button>
        <button class="btn" style="background-color: #777; margin-left: 10px;" onclick="cancelCheckout()">Cancel</button>
    </div>

    <!-- Order Confirmation View -->
    <div id="confirmation-view" class="full-page-view">
        <div class="success-icon">✔️</div>
        <h2 style="color: #2e7d32; font-size: 32px;">Order Confirmed!</h2>
        <p style="font-size: 20px;">Thank you for shopping with Local Market.</p>
        <p id="order-status-text" style="font-size: 18px; margin-bottom: 40px; font-weight: bold; color: #d32f2f;"></p>
        <button class="btn" style="font-size: 18px; padding: 12px 30px;" onclick="goHome()">Explore More / Go to Home Page</button>
    </div>

    <!-- JavaScript Logic -->
    <script>
        // Cart object to store items grouped by ID
        // Format: { "p1": { name: "Fresh Apples", price: 120, qty: 2 }, ... }
        let cart = {};

        // Run this initially to load "Add to Cart" buttons
        window.onload = function() {
            updateAllUI();
        };

        // --- Toast Notification Logic ---
        let toastTimeout;
        function showToast(message) {
            let toast = document.getElementById("toast");
            toast.innerText = message;
            toast.className = "toast show";
            
            clearTimeout(toastTimeout);
            toastTimeout = setTimeout(function(){ 
                toast.className = toast.className.replace("show", ""); 
            }, 3000);
        }

        // --- Cart Modal Logic ---
        function openCartModal() {
            document.getElementById("cart-modal").style.display = "block";
        }

        function closeCartModal() {
            document.getElementById("cart-modal").style.display = "none";
        }

        // Add initial product to cart
        function addToCart(id, name, price) {
            if (!cart[id]) {
                cart[id] = { name: name, price: price, qty: 1 };
                showToast(name + " added to cart!");
            }
            updateAllUI();
        }

        // Adjust quantity of existing item (+1 or -1)
        function updateQty(id, delta) {
            if (cart[id]) {
                cart[id].qty += delta;
                
                // Remove item if quantity falls to 0
                if (cart[id].qty <= 0) {
                    delete cart[id];
                }
            }
            updateAllUI();
        }

        // Remove item completely from modal
        function removeItem(id) {
            if (cart[id]) {
                delete cart[id];
                updateAllUI();
            }
        }

        // --- Master UI Update Function ---
        function updateAllUI() {
            let totalItems = 0;
            let totalPrice = 0;
            let cartItemsHTML = "";

            // Loop through all items currently in the cart object
            for (let id in cart) {
                let item = cart[id];
                totalItems += item.qty;
                let itemTotal = item.price * item.qty;
                totalPrice += itemTotal;

                // Build HTML for the Cart Modal list
                cartItemsHTML += `
                    <div class="cart-item">
                        <div class="cart-item-info">
                            <strong>${item.name}</strong> <br>
                            ₹${item.price} x ${item.qty} = <strong>₹${itemTotal}</strong>
                        </div>
                        <div class="modal-qty-controls">
                            <button onclick="updateQty('${id}', -1)">-</button>
                            <span>${item.qty}</span>
                            <button onclick="updateQty('${id}', 1)">+</button>
                        </div>
                        <button class="remove-btn" onclick="removeItem('${id}')">Remove</button>
                    </div>
                `;
            }

            // Update modal content
            let cartContainer = document.getElementById("cart-items-container");
            if (totalItems === 0) {
                cartContainer.innerHTML = "<p style='text-align: center; color: #777;'>Your cart is empty.</p>";
            } else {
                cartContainer.innerHTML = cartItemsHTML;
            }

            // Update Total Price and Counters
            document.getElementById("cart-total-price").innerText = totalPrice;
            document.getElementById("nav-cart-count").innerText = totalItems;
            document.getElementById("float-cart-count").innerText = totalItems;

            // Update Product Card Buttons (swap between "Add to Cart" and Quantity Controls)
            let btnContainers = document.querySelectorAll('.btn-container');
            
            btnContainers.forEach(container => {
                let id = container.id.replace('btn-', ''); // Extract 'p1' from 'btn-p1'
                let name = container.getAttribute('data-name');
                let price = parseInt(container.getAttribute('data-price'));

                if (cart[id]) {
                    // Item is in cart, show quantity controls
                    container.innerHTML = `
                        <div class="qty-controls">
                            <button onclick="updateQty('${id}', -1)">-</button>
                            <span>${cart[id].qty} in Cart</span>
                            <button onclick="updateQty('${id}', 1)">+</button>
                        </div>
                    `;
                } else {
                    // Item not in cart, show default Add button
                    container.innerHTML = `<button onclick="addToCart('${id}', '${name}', ${price})">Add to Cart</button>`;
                }
            });
        }

        // --- Payment Option Toggle Logic ---
        function togglePaymentDetails() {
            let selected = document.querySelector('input[name="payment"]:checked').value;
            
            document.getElementById('cod-details').style.display = (selected === 'cod') ? 'block' : 'none';
            document.getElementById('upi-details').style.display = (selected === 'upi') ? 'block' : 'none';
            document.getElementById('card-details').style.display = (selected === 'card') ? 'block' : 'none';
        }

        // --- Checkout & Form Submissions ---
        function checkout() {
            // Check if object is empty
            if (Object.keys(cart).length === 0) {
                showToast("Your cart is empty! Add products before checking out.");
            } else {
                let total = document.getElementById("cart-total-price").innerText;
                
                // Hide main store and cart modal, show checkout view
                closeCartModal();
                document.getElementById("main-store-view").style.display = "none";
                document.getElementById("checkout-view").style.display = "block";
                
                // Update total in checkout view
                document.getElementById("checkout-total-price").innerText = total;
                document.getElementById("cod-amount").innerText = total;
                document.getElementById("upi-amount").innerText = total;

                // Reset payment method to default (COD)
                document.querySelector('input[name="payment"][value="cod"]').checked = true;
                togglePaymentDetails();
            }
        }

        function cancelCheckout() {
            // Go back to the main store view
            document.getElementById("checkout-view").style.display = "none";
            document.getElementById("main-store-view").style.display = "block";
        }

        function confirmOrder() {
            let total = document.getElementById("checkout-total-price").innerText;
            let selectedPayment = document.querySelector('input[name="payment"]:checked').value;
            let statusText = document.getElementById("order-status-text");

            // Update confirmation text based on payment method
            if (selectedPayment === 'cod') {
                statusText.innerText = "Amount due on delivery: ₹" + total;
                statusText.style.color = "#d32f2f"; // Red color for due amount
            } else {
                statusText.innerText = "Amount paid successfully.";
                statusText.style.color = "#2e7d32"; // Green color for paid amount
            }

            // Hide checkout view, show confirmation view
            document.getElementById("checkout-view").style.display = "none";
            document.getElementById("confirmation-view").style.display = "block";
        }

        function goHome() {
            // Reset Cart to empty
            cart = {}; 
            updateAllUI();
            
            // Hide confirmation view, show main store view
            document.getElementById("confirmation-view").style.display = "none";
            document.getElementById("main-store-view").style.display = "block";
            
            // Scroll back to the top of the page
            window.scrollTo(0, 0);
        }

        function handleContactSubmit(event) {
            event.preventDefault(); 
            let name = document.getElementById("name").value;
            showToast("Thank you, " + name + "! Your message has been sent.");
            event.target.reset();
        }
    </script>
</body>
</html>
