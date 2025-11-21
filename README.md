<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Autodops</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #0d0d0d;
            color: #ffffff;
        }
        header {
            background: #111827;
            padding: 20px;
            text-align: center;
            color: #38bdf8;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background: #1f2937;
            padding: 10px;
        }
        nav a {
            color: #e5e7eb;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: linear-gradient(to bottom right, #0ea5e9, #1e3a8a);
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        .section {
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }
        .card {
            background: #1f2937;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #111827;
            margin-top: 40px;
        }
        .btn {
            display: inline-block;
            padding: 12px 20px;
            border-radius: 8px;
            background: #111827;
            color: #38bdf8;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            box-shadow: 0 6px 18px rgba(0,0,0,0.2);
        }
        .btn:hover {
            transform: translateY(-2px);
            transition: transform 150ms ease;
        }
    </style>
</head>
<body>

<header>
    <h1>AUDOTOPS</h1>
    <p>A COMPLETE THRIFT SHOP</p>
    </header>

<nav>
    <a href="#home">Home</a>
    <a href="#features">Features</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
    <h1>WELCOME TO AUDOTOPS</h1>
    <p>Genuine.Comfortable.Trustable</p>
    <!-- External link button: opens another website in a new tab -->
    <a class="btn" href="sura.html" >GO TO SHOP</a>
</section>

<section class="section" id="features">
    <h2>Features</h2>

    <div class="card">
        <h3>⚡ Fast Delivery</h3>
        <p>we will deliver the item within 2-3 days.</p>
    </div>

    <div class="card">
        <h3>📱 Responsive Design</h3>
        <p>Looks great on mobile, tablet, and desktop.</p>
    </div>
</section>

<section class="section" id="about">
    <h2>About AUDOTOPS</h2>
    <p>
        Autodops is a modern platform designed for automation, speed, and a clean user experience.
        Whether you're building tools, dashboards, or services, Autodops gives you the power to create efficiently.
    </p>
</section>

<section class="section" id="contact">
    <h2>Contact</h2>
    <p>Email: support@autodops.com</p>
    <p>Instagram: @autodops</p>
</section>

<footer>
    © 2025 Autodops. All rights reserved.
</footer>

</body>
</html>
