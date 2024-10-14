<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mi unica 内衣公司</title>
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
            background-image: url('logo_image_url_here'); /* 在这里插入Logo图片的URL */
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
        <h1>mi unica 内衣公司</h1>
    </header>

    <nav>
        <a href="#home">首页</a>
        <a href="#products">产品</a>
        <a href="#about">关于我们</a>
        <a href="#contact">联系我们</a>
    </nav>

    <section class="hero">
        <h1>欢迎来到 mi unica</h1>
    </section>

    <section class="products" id="products">
        <div class="product">
            <img src="https://example.com/product1.jpg" alt="产品1">
            <h3>内衣系列1</h3>
            <p>柔软舒适，完美贴合。</p>
        </div>
        <div class="product">
            <img src="https://example.com/product2.jpg" alt="产品2">
            <h3>内衣系列2</h3>
            <p>设计时尚，质量优异。</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 mi unica 内衣公司. 版权所有。</p>
        <div class="contact-info">
            <p>电话: 937786553</p>
            <p>邮箱: <a href="mailto:xu23355@gmail.com">xu23355@gmail.com</a></p>
        </div>
    </footer>

</body>
</html>
