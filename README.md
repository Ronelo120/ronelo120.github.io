<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Website</title>
    <style>
        /* General Reset */
        * 
        {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body 
        {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header 
        {
            background-color: #ff5733;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 
        {
            margin: 0;
        }
        nav 
        {
            background: #333;
            color: white;
            padding: 0.5rem;
            text-align: center;
        }
        nav a 
        {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }
        nav a:hover 
        {
            text-decoration: underline;
        }
        .container 
        {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
        }
        .products 
        {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }
        .product 
        {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            width: 300px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .product:hover 
        {
            transform: scale(1.05);
        }
        .product img 
        {
            max-width: 100%;
            height: auto;
        }
        .product h3 
        {
            margin: 1rem 0;
        }
        .product p 
        {
            color: #555;
            padding: 0 1rem;
        }
        .product .price 
        {
            font-size: 1.2rem;
            color: #ff5733;
            margin-bottom: 1rem;
        }
        .product button 
        {
            background-color: #ff5733;
            border: none;
            color: white;
            cursor: pointer;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .product button:hover 
        {
            background-color: #e74c3c;
        }
        footer 
        {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our E-Commerce Store</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <div class="container">
        <section class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 1">
                <h3>Product 1</h3>
                <p>High-quality product to meet your needs.</p>
                <p class="price">&#8369; 500.00</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 2">
                <h3>Product 2</h3>
                <p>Experience the best with this amazing item.</p>
                <p class="price">&#8369; 750.00</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 3">
                <h3>Product 3</h3>
                <p>Unmatched quality at an affordable price.</p>
                <p class="price">&#8369; 1000.00</p>
                <button>Add to Cart</button>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 E-Commerce Store. All Rights Reserved.</p>
    </footer>
</body>
</html>
