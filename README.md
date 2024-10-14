<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mi unica Lingerie</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #f8b6c1;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            padding: 14px 20px;
            display: block;
            color: white;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            background-image: url('logo_image_url_here'); /* Insert the URL of your logo image here */
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            font-size: 50px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }
        .product {
            background-color: #fff;
            width: 300px;
            margin: 10px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .product h3 {
            font-size: 22px;
            margin: 10px 0;
        }
        .product p {
            font-size: 16px;
            color: #777;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .contact-info {
            margin-top: 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <header>
        <h1>mi unica Lingerie</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h1>Welcome to mi unica</h1>
    </section>

    <section class="products" id="products">
        <div class="product">
            <img src="https://example.com/product1.jpg" alt="Product 1">
            <h3>Lingerie Series 1</h3>
            <p>Soft, comfortable, and perfectly fitted.</p>
        </div>
        <div class="product">
            <img src="https://example.com/product2.jpg" alt="Product 2">
            <h3>Lingerie Series 2</h3>
            <p>Fashionable design, superior quality.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 mi unica Lingerie. All rights reserved.</p>
        <div class="contact-info">
            <p>Phone: 937786553</p>
            <p>Email: <a href="mailto:xu23355@gmail.com">xu23355@gmail.com</a></p>
        </div>
    </footer>

</body>
</html>
