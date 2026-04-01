<!DOCTYPE html>
<html>
<head>
    <title>Travel Website</title>

    <!-- External CSS -->
    <link rel="stylesheet" href="style.css">

    <!-- Internal CSS -->
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #064e3b;
            color: white;
        }

        nav {
            background-color: #022c22;
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #a7f3d0;
        }

        .container {
            width: 90%;
            margin: auto;
            padding: 20px;
            text-align: center;
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
            border-radius: 12px;
            overflow: hidden;
        }

        .image-box img {
            width: 100%;
            height: 100%;
        }

        .video-box {
            margin: 20px auto;
            background-color: #065f46;
            padding: 15px;
            border-radius: 12px;
            width: 60%;
        }

        table {
            width: 90%;
            margin: 20px auto;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid white;
            padding: 10px;
        }

        th {
            background-color: #065f46;
        }

        ul, ol {
            text-align: left;
            width: 60%;
            margin: 20px auto;
        }

        .form-container {
            width: 60%;
            margin: 30px auto;
            background-color: #065f46;
            padding: 20px;
            border-radius: 12px;
        }

        input, select {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
        }

        button {
            padding: 10px 20px;
            background-color: #022c22;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background-color: #022c22;
            padding: 15px;
            margin-top: 30px;
            text-align: center;
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
            <li><a href="#">Bookings</a></li>
        </ul>
    </nav>

    <!-- Content -->
    <div class="container">

        <h1 style="color:#a7f3d0;">Explore Amazing Destinations</h1>

        <!-- Paragraphs -->
        <p>
            Traveling gives you the opportunity to experience different cultures, landscapes, 
            and lifestyles. From the beautiful beaches of the coast to the wildlife safaris 
            in national parks, every journey creates unforgettable memories and experiences.
        </p>

        <p>
            Whether you are looking for adventure, relaxation, or cultural exploration, 
            there is always something new to discover. Traveling helps you grow, learn, 
            and appreciate the beauty of the world around you.
        </p>

        <!-- Images -->
        <h2>Popular Destinations</h2>
        <div class="image-section">

            <div class="image-box">
                <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e">
            </div>

            <div class="image-box">
                <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470">
            </div>

            <div class="image-box">
                <img src="https://images.unsplash.com/photo-1467269204594-9661b134dd2b">
            </div>

            <div class="image-box">
                <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee">
            </div>

            <div class="image-box">
                <img src="https://images.unsplash.com/photo-1493558103817-58b2924bce98">
            </div>

        </div>

        <!-- Videos -->
        <h2>Travel Videos</h2>

        <div class="video-box">
            <video width="100%" controls>
                <source src="travel1.mp4" type="video/mp4">
            </video>
        </div>

        <div class="video-box">
            <video width="100%" controls>
                <source src="travel2.mp4" type="video/mp4">
            </video>
        </div>

        <!-- Table -->
        <h2>Travel Packages</h2>
        <table>
            <tr>
                <th>Destination</th>
                <th>Price</th>
                <th>Duration</th>
            </tr>
            <tr>
                <td>Mombasa</td>
                <td>KES 15,000</td>
                <td>3 Days</td>
            </tr>
            <tr>
                <td>Maasai Mara</td>
                <td>KES 25,000</td>
                <td>4 Days</td>
            </tr>
        </table>

        <!-- List -->
        <h2>Why Travel?</h2>
        <ul>
            <li>Explore new cultures</li>
            <li>Relax and refresh</li>
            <li>Create memories</li>
        </ul>

        <!-- Form -->
        <div class="form-container">
            <h2>Book a Trip</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Email" required>

                <select>
                    <option>Select Destination</option>
                    <option>Mombasa</option>
                    <option>Maasai Mara</option>
                </select>

                <button type="submit">Book Now</button>
            </form>
        </div>

    </div>

    <!-- Footer -->
    <footer>
        <p>© 2026 Travel Kenya | All Rights Reserved</p>
    </footer>

</body>
</html>
