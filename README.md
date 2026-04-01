<!DOCTYPE html>
<html>
<head>
    <title>Travel Kenya</title>

    <!-- External CSS -->
    <link rel="stylesheet" href="style.css">

    <!-- Internal CSS -->
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #064e3b;
            color: white;
            text-align: center;
        }

        nav {
            background-color: #022c22;
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        .container {
            width: 90%;
            margin: auto;
            padding: 20px;
        }

        .image-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }

        .image-box {
            width: 250px;
            height: 180px;
            border-radius: 10px;
            overflow: hidden;
        }

        .image-box img {
            width: 100%;
            height: 100%;
        }

        .video-box {
            width: 60%;
            margin: 20px auto;
            background-color: #065f46;
            padding: 15px;
            border-radius: 10px;
        }

        footer {
            background-color: #022c22;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <nav>
        <h2>Travel Kenya</h2>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Destinations</a></li>
        </ul>
    </nav>

    <div class="container">

        <!-- Inline CSS -->
        <h1 style="color:#a7f3d0;">Explore the World</h1>

        <!-- Paragraphs -->
        <p>
            Traveling allows you to experience new environments, cultures, and traditions. 
            From coastal beaches to wildlife safaris, every destination offers something unique 
            and exciting to explore.
        </p>

        <p>
            Whether you enjoy adventure, relaxation, or learning new cultures, traveling helps 
            you grow and creates unforgettable memories that last a lifetime.
        </p>

        <!-- Images -->
        <h2>Popular Destinations</h2>
        <div class="image-section">

            <div class="image-box">
                <img src="https://picsum.photos/400/300?random=1">
            </div>

            <div class="image-box">
                <img src="https://picsum.photos/400/300?random=2">
            </div>

            <div class="image-box">
                <img src="https://picsum.photos/400/300?random=3">
            </div>

            <div class="image-box">
                <img src="https://picsum.photos/400/300?random=4">
            </div>

            <div class="image-box">
                <img src="https://picsum.photos/400/300?random=5">
            </div>

        </div>

        <!-- Videos -->
        <h2>Travel Videos</h2>

        <div class="video-box">
            <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/Scxs7L0vhZ4"
                frameborder="0" allowfullscreen>
            </iframe>
        </div>

        <div class="video-box">
            <iframe width="100%" height="315"
                src="https://www.youtube.com/embed/Zn6o0rXhGkY"
                frameborder="0" allowfullscreen>
            </iframe>
        </div>

    </div>

    <footer>
        <p>© 2026 Travel Kenya</p>
    </footer>

</body>
</html>
        
