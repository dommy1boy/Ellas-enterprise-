# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ella's Enterprise | Fashion & Style</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #fff7fb;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #ff4d88, #ff9966);
            color: #fff;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 26px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        .hero {
            padding: 80px 20px;
            text-align: center;
            background: #ffe6ef;
        }

        .hero h2 {
            font-size: 42px;
            color: #ff3366;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
        }

        .hero a {
            background: #ff3366;
            color: #fff;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 60px 20px;
            max-width: 1200px;
            margin: auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
        }

        .section-title h3 {
            font-size: 32px;
            color: #ff3366;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .product {
            background: #fff;
            border-radius: 12px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.1);
            overflow: hidden;
            text-align: center;
        }

        .product img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        .product-info {
            padding: 20px;
        }

        .product-info h4 {
            font-size: 18px;
            margin-bottom: 8px;
        }

        .price {
            font-size: 18px;
            font-weight: bold;
            color: #ff3366;
            margin-bottom: 15px;
        }

        .product-info button {
            background: #ff3366;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 20px;
            cursor: pointer;
            font-weight: bold;
        }

        .about {
            background: #fff0f6;
            border-radius: 12px;
            padding: 40px;
            text-align: center;
        }

        .about h3 {
            color: #ff3366;
            margin-bottom: 15px;
        }

        .cta {
            background: linear-gradient(90deg, #ff4d88, #ff9966);
            color: #fff;
            text-align: center;
            padding: 70px 20px;
        }

        .cta h3 {
            font-size: 34px;
            margin-bottom: 15px;
        }

        .cta a {
            background: #fff;
            color: #ff3366;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            background: #222;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
            font-size: 14px;
        }

        footer a {
            color: #ff99bb;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Ella's Enterprise</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
        <a href="#">Cart</a>
    </nav>
</header>

<section class="hero">
    <h2>Style That Speaks Elegance</h2>
    <p>Discover beautiful, classy, and affordable fashion at Ella's Enterprise.</p>
    <a href="#">Shop Now</a>
</section>

<section>
    <div class="section-title">
        <h3>Our Collections</h3>
    </div>

    <div class="products">
        <div class="product">
            <img src="https://images.unsplash.com/photo-1521334884684-d80222895322">
            <div class="product-info">
                <h4>Classic Female Gown</h4>
                <div class="price">₦12,000</div>
                <button>Add to Cart</button>
            </div>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb">
            <div class="product-info">
                <h4>Elegant Office Wear</h4>
                <div class="price">₦20,000</div>
                <button>Add to Cart</button>
            </div>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1520975922284-6c06a6f7f7a5">
            <div class="product-info">
                <h4>Stylish Casual Outfit</h4>
                <div class="price">₦15,000</div>
                <button>Add to Cart</button>
            </div>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1483985988355-763728e1935b">
            <div class="product-info">
                <h4>Luxury Evening Dress</h4>
                <div class="price">₦25,000</div>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>
</section>

<section class="about">
    <h3>About Ella's Enterprise</h3>
    <p>
        Ella's Enterprise is a fashion brand dedicated to delivering high-quality,
        trendy, and affordable clothing for confident individuals who love style and elegance.
    </p>
</section>

<section class="cta">
    <h3>Upgrade Your Wardrobe Today</h3>
    <p>Beautiful outfits. Affordable prices. Timeless style.</p>
    <a href="#">Start Shopping</a>
</section>

<footer>
    <p>© 2026 Ella's Enterprise. All Rights Reserved.</p>
    <p>
        <a href="#">Privacy Policy</a> |
        <a href="#">Terms & Conditions</a> |
        <a href="#">Contact Us</a>
    </p>
</footer>

</body>
</html>
