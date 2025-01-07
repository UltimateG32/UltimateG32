<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Toys Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #ff6347;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 2rem;
            text-align: center;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
        }
        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            width: 250px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            color: #333;
            margin: 1rem 0 0.5rem;
        }
        .product p {
            color: #777;
            font-size: 0.9rem;
        }
        .product button {
            background-color: #ff6347;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }
        .product button:hover {
            background-color: #e5533d;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Happy Toys Store</h1>
        <p>Your one-stop shop for fun and joy!</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="products">
        <h2>Our Popular Toys</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/250" alt="Toy Car">
                <h3>Toy Car</h3>
                <p>Exciting remote-controlled car for kids!</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250" alt="Doll">
                <h3>Doll</h3>
                <p>Cute and cuddly doll for endless fun.</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250" alt="Building Blocks">
                <h3>Building Blocks</h3>
                <p>Creative building blocks for young minds.</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Happy Toys Store. All rights reserved.</p>
    </footer>
</body>
</html>
