<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Explorer</title>

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

        /* Navigation Bar */
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
            padding: 0;
        }

        nav ul li {
            display: inline;
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
            width: 80%;
        }

        table {
            width: 80%;
            margin: auto;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid white;
            padding: 10px;
        }

        th {
            background-color: #065f46;
        }

        /* Booking Form */
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

        button:hover {
            background-color: #0f766e;
        }

        footer {
            background-color: #022c22;
            padding: 15px;
            margin-top: 30px;
            text-align: center;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
                text-align: center;
            }

            nav ul {
                flex-direction: column;
                gap: 10px;
            }

            .image-section {
                flex-direction: column;
                align-items: center;
            }

            .form-container {
                width: 90%;
            }

            table {
                width: 100%;
            }
        }
    </style>
</head>

<body>

<!-- Navigation -->
<nav>
    <h2 style="color:#bbf7d0;">Travel Explorer</h2>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#destinations">Destinations</a></li>
        <li><a href="#booking">Booking</a></li>
        <li><a href="#videos">Videos</a></li>
    </ul>
</nav>

<div class="container">

    <h1 style="color:#bbf7d0;">Explore The World With Us</h1>

    <p>
        Traveling is one of the most rewarding experiences in life. It allows you to discover 
        new cultures, explore beautiful landscapes, and meet people from different backgrounds. 
        From relaxing beach holidays to exciting city adventures, every journey creates memories 
        that last a lifetime. Our travel services are designed to give you comfort, safety, and 
        unforgettable experiences wherever you go.
    </p>

    <p>
        Whether you dream of visiting tropical islands, historic cities, or modern skylines, 
        we provide carefully planned travel packages to suit your needs. Our team ensures smooth 
        booking, comfortable accommodation, and exciting activities throughout your trip. 
        Start your adventure today and let us turn your travel dreams into reality.
    </p>

    <h2 id="destinations">Top Destinations</h2>

    <div class="image-section">
        <div class="image-box">
            <img src="https://source.unsplash.com/400x300/?paris" alt="Paris">
        </div>
        <div class="image-box">
            <img src="https://source.unsplash.com/400x300/?maldives" alt="Maldives">
        </div>
        <div class="image-box">
            <img src="https://source.unsplash.com/400x300/?dubai" alt="Dubai">
        </div>
        <div class="image-box">
            <img src="https://source.unsplash.com/400x300/?newyork" alt="New York">
        </div>
        <div class="image-box">
            <img src="https://source.unsplash.com/400x300/?tokyo" alt="Tokyo">
        </div>
    </div>

    <h2>Travel Packages</h2>

    <table>
        <tr>
            <th>Destination</th>
            <th>Duration</th>
            <th>Price</th>
        </tr>
        <tr>
            <td>Paris</td>
            <td>5 Days</td>
            <td>$1200</td>
        </tr>
        <tr>
            <td>Maldives</td>
            <td>7 Days</td>
            <td>$2000</td>
        </tr>
        <tr>
            <td>Dubai</td>
            <td>4 Days</td>
            <td>$900</td>
        </tr>
    </table>

    <h2 id="booking">Book Your Trip</h2>

    <div class="form-container">
        <form>
            <input type="text" placeholder="Full Name" required>
            <input type="email" placeholder="Email Address" required>
            <select required>
                <option value="">Select Destination</option>
                <option>Paris</option>
                <option>Maldives</option>
                <option>Dubai</option>
            </select>
            <input type="date" required>
            <button type="submit">Book Now</button>
        </form>
    </div>

    <h2 id="videos">Travel Videos</h2>

    <div class="video-box">
        <iframe width="100%" height="315"
        src="https://www.youtube.com/embed/5U3n4l3XkW0"
        frameborder="0" allowfullscreen></iframe>
    </div>

    <div class="video-box">
        <iframe width="100%" height="315"
        src="https://www.youtube.com/embed/lJIrF4YjHfQ"
        frameborder="0" allowfullscreen></iframe>
    </div>

</div>

<footer>
    © 2026 Travel Explorer | Designed for Professional Presentation
</footer>

</body>
</html>
