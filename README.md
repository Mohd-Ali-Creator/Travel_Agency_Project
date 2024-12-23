
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Tour and travel website offering great packages and destinations.">
    <title>International Tour & Travel Adventures</title>
    <link rel="stylesheet" href="pop-up.html">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(120deg, #a1c4fd 0%, #c2e9fb 100%);
            color: #333;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background: #0077b6;
            color: #fff;
            padding: 1.5rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            margin: 0;
            font-size: 2rem;
        }

        .search-bar {
            display: flex;
            align-items: center;
        }

        .search-bar input {
            padding: 0.5rem;
            font-size: 1rem;
            border: none;
            border-radius: 5px;
        }

        .search-bar button {
            padding: 0.5rem 1rem;
            font-size: 1rem;
            background: #ffd700;
            color: #0077b6;
            border: none;
            border-radius: 5px;
            margin-left: 0.5rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .search-bar button:hover {
            background: #ffcc00;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            gap: 1.5rem;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ffd700;
        }

        .hero {
            background: url('images/hero-bg.jpg') center center/cover no-repeat;
            color: #fff;
            text-align: center;
            padding: 6rem 2rem;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.25rem;
            margin-bottom: 2rem;
        }

        .btn {
            background: #ffd700;
            color: #0077b6;
            padding: 0.75rem 1.5rem;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            text-decoration: none;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #ffcc00;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 2rem auto;
            background: rgba(255, 255, 255, 0.9);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
            padding: 2rem;
        }

        .container h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
        }

        .destination-cards {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }

        .card {
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            width: calc(33.333% - 2rem);
            transition: transform 0.3s ease;
        }

        .card img {
            width: 100%;
            height: auto;
        }

        .card h3 {
            font-size: 1.5rem;
            margin: 1rem 0;
            text-align: center;
        }

        .card p {
            padding: 0 1rem;
            text-align: center;
        }

        .card .btn {
            display: block;
            margin: 1rem auto;
            text-align: center;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .about-us, .booking, .contact {
            background: #f9f9f9;
            padding: 2rem;
            border-radius: 10px;
            margin-bottom: 2rem;
        }

        .about-us p, .contact p {
            font-size: 1.1rem;
            line-height: 1.6;
        }

        .contact-info {
            font-size: 1.1rem;
        }

        footer {
            background: #0077b6;
            color: #fff;
            text-align: center;
            padding: 1rem;
            margin-top: auto;
        }

        footer .social-icons a {
            color: #fff;
            margin: 0 0.5rem;
            font-size: 1.2rem;
            transition: color 0.3s ease;
        }

        footer .social-icons a:hover {
            color: #ffd700;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <h1>AL-ALI INTERNATIONAL TOUR AND TRAVEL</h1>
        </div>
        <div class="search-bar">
            <input type="text" placeholder="Search...">
            <button type="button" onclick="search()">Search</button>
        </div>
        <nav>
            <ul class="nav-links">
                <li><a href="home.html">Home</a></li>
                <li><a href="#destinations">Destinations</a></li>
                <li><a href="pop-up.html">About Us</a></li>
                <li><a href="flight.html">Flight</a></li>
                <li><a href="hotel.html">Hotel</a></li>
            </ul>
            <!-- <div class="hamburger" id="hamburger-menu">
                <i class="fas fa-bars"></i>
            </div> -->
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Explore the World with Us</h2>
            <p>Your dream vacation is just a click away.</p>
            <a href="#contact" class="btn">Get Started</a>
        </div>
    </section>

    <section id="destinations" class="destinations">
        <div class="container">
            <h2>Popular Destinations</h2>
            <div class="destination-cards">
                <div class="card">
                    <img src="https://storage.googleapis.com/pod_public/1300/174593.jpg" alt="Paris">
                    <h3>Paris</h3>
                    <p>The city of love, Eiffel Tower awaits you!</p>
                    <a href="#booking" class="btn">Book Your Journey</a>
                </div>
                <div class="card">
                    <img src="https://images.pexels.com/photos/3913353/pexels-photo-3913353.jpeg?cs=srgb&dl=statue-of-liberty-new-york-3913353.jpg&fm=jpg" alt="New York">
                    <h3>New York</h3>
                    <p>Explore the Big Apple, a city full of life!</p>
                    <a href="#booking" class="btn">Book Your Trip</a>
                </div>
                <div class="card">
                    <img src="https://i.pinimg.com/originals/20/72/17/207217fa531f3ea85518c2a3d032e863.jpg" alt="Tokyo">
                    <h3>Tokyo</h3>
                    <p>A perfect mix of tradition and technology.</p>
                    <a href="#booking" class="btn">Book Your Tour</a>
                </div>
                <div class="card">
                    <img src="https://ilmfeed.com/wp-content/uploads/2016/07/2a-758x1074.jpg" alt="Saudi Arabia">
                    <h3>Saudi Arabia (Hajj & Umrah)</h3>
                    <p>Embark on a sacred journey to Mecca and Medina for Hajj or Umrah.</p>
                    <a href="#booking" class="btn">Book Your Pilgrimage</a>
                </div>
                <div class="card">
                    <img src="https://wallpapers.com/images/hd/modern-iphone-aqy704zlc1coxh9f.jpg" alt="Dubai">
                    <h3>Dubai</h3>
                    <p>A perfect place of enjoy.</p>
                    <a href="#booking" class="btn">Book Your Trip</a>
                </div>
                <div class="card">
                    <img src="https://th.bing.com/th/id/OIP.aexqb8Yy6NcVD0AI7RtQ5wAAAA?w=333&h=499&rs=1&pid=ImgDetMain" alt="Qatar">
                    <h3>Welcome to Qatar</h3>
                    <p>A way to Adventure to Qatar.</p>
                    <a href="#booking" class="btn">Book Your Way</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about-us">
        <div class="container">
            <h2>About Us</h2>
            <p>We are AL-ALI INTERNATIONAL TOUR AND TRAVEL, a passionate group of travel enthusiasts dedicated to helping you find the best destinations, amazing experiences, and top-class travel services.</p>
            <p>We believe that travel is not just about visiting places, but about making memories that last a lifetime. Join us on a journey that will change your life!</p>
        </div>
    </section>

    <section id="booking" class="booking">
        <div class="container">
            <h2>Book Your Trip</h2>
            <form id="booking-form" action="#">
                <label for="destination">

                    <section id="Payment" class ="Payment"></section>
                    <div class="container">
                        <h2>Pay Now And Get Exiting Offers</h2>
                        <form id="Payment-form" action="#">
                    </div>
                    </section>
