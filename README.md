<!DOCTYPE html>
<html>
<head>
    <title>Explore India</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        header {
            background: url('https://images.unsplash.com/photo-1524492412937-b28074a5d7da') no-repeat center center/cover;
            height: 400px;
            color: white;
            text-align: center;
            padding-top: 150px;
        }

        header h1 {
            font-size: 50px;
            margin: 0;
        }

        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-size: 18px;
        }

        nav a:hover {
            color: yellow;
        }

        .container {
            padding: 40px;
            text-align: center;
        }

        .places {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .card {
            background: white;
            width: 300px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            overflow: hidden;
        }

        .card img {
            width: 100%;
            height: 200px;
        }

        .card h3 {
            margin: 10px 0;
        }

        .card p {
            padding: 0 15px 15px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>Explore Incredible India</h1>
    <p>Discover the beauty of India</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Destinations</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
</nav>

<div class="container">
    <h2>Popular Tourist Places</h2>

    <div class="places">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1548013146-72479768bada" alt="Taj Mahal">
            <h3>Taj Mahal</h3>
            <p>A symbol of love located in Agra.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Goa Beach">
            <h3>Goa</h3>
            <p>Famous for beaches and nightlife.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308" alt="Kerala">
            <h3>Kerala</h3>
            <p>Known as God's Own Country with beautiful backwaters.</p>
        </div>
    </div>
</div>

<footer>
    <p>© 2026 Explore India | All Rights Reserved</p>
</footer>

</body>
</html>