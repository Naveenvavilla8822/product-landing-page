# product-landing-page
it is a product landing page website design code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Product Landing Page</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        #hero {
            text-align: center;
            padding: 2em 0;
        }

        #hero img {
            max-width: 100%;
            height: auto;
        }

        #cta {
            text-align: center;
            margin: 2em 0;
        }

        .btn {
            display: inline-block;
            padding: 1em 2em;
            text-decoration: none;
            background-color: #333;
            color: #fff;
            border-radius: 5px;
        }

        #features {
            background-color: #fff;
            padding: 2em 0;
        }

        .feature {
            text-align: center;
            margin: 0 2%;
            width: 30%;
            display: inline-block;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Your Product Name</h1>
        </div>
    </header>

    <div id="hero">
        <div class="container">
            <img src="product-image.jpg" alt="Product Image">
        </div>
    </div>

    <div id="cta">
        <p>Experience the revolution. Buy now!</p>
        <a href="#" class="btn">Buy Now</a>
    </div>

    <div id="features">
        <div class="container">
            <div class="feature">
                <h2>Feature 1</h2>
                <p>Description of Feature 1.</p>
            </div>
            <div class="feature">
                <h2>Feature 2</h2>
                <p>Description of Feature 2.</p>
            </div>
            <div class="feature">
                <h2>Feature 3</h2>
                <p>Description of Feature 3.</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Your Company Name. All rights reserved.</p>
    </footer>

</body>
</html>
