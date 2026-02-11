<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arnav Web Studio | Websites Made for You</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color: white;
            line-height: 1.6;
            overflow-x: hidden;
        }

        /* Subtle texture overlay */
        body::before {
            content: "";
            position: fixed;
            width: 100%;
            height: 100%;
            background-image: radial-gradient(rgba(255,255,255,0.03) 1px, transparent 1px);
            background-size: 3px 3px;
            z-index: -1;
        }

        header {
            padding: 20px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(15, 23, 42, 0.8);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
        }

        header h1 {
            background: linear-gradient(90deg, #38bdf8, #22c55e);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        header a {
            color: #cbd5e1;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
            transition: 0.3s;
        }

        header a:hover {
            color: #38bdf8;
        }

        .hero {
            padding: 100px 10%;
            text-align: center;
        }

        .hero h2 {
            font-size: 3rem;
            margin-bottom: 20px;
            background: linear-gradient(90deg, #38bdf8, #22c55e);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            font-size: 1.2rem;
            color: #cbd5e1;
            margin-bottom: 35px;
        }

        .btn {
            background: linear-gradient(90deg, #38bdf8, #22c55e);
            padding: 14px 28px;
            border-radius: 30px;
            text-decoration: none;
            color: black;
            font-weight: 600;
            box-shadow: 0 0 15px rgba(56,189,248,0.4);
            transition: 0.3s;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 0 25px rgba(34,197,94,0.6);
        }

        .section {
            padding: 70px 10%;
            text-align: center;
        }

        .dark {
            background: linear-gradient(135deg, #1e293b, #0f172a);
        }

        .service-boxes, .pricing-boxes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            margin-top: 40px;
        }

        .box {
            background: rgba(255,255,255,0.05);
            padding: 30px;
            border-radius: 12px;
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255,255,255,0.08);
            transition: 0.3s;
        }

        .box:hover {
            transform: translateY(-6px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.4);
        }

        .box h4 {
            margin-bottom: 15px;
            color: #38bdf8;
        }

        .price {
            font-size: 2rem;
            margin: 15px 0;
            color: #22c55e;
            font-weight: bold;
        }

        .contact a {
            display: block;
            margin-top: 12px;
            color: #38bdf8;
            font-weight: 500;
            text-decoration: none;
            transition: 0.3s;
        }

        .contact a:hover {
            color: #22c55e;
        }

        footer {
            text-align: center;
            padding: 25px;
            background: #0b1220;
            color: #94a3b8;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Arnav Web Studio</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#pricing">Pricing</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>I Build Professional Websites for Your Business</h2>
    <p>Custom, modern, mobile-friendly websites made to help you grow online.</p>
    <a href="#contact" class="btn">Order Your Website</a>
</section>

<section id="services" class="section dark">
    <h3>My Services</h3>
    <div class="service-boxes">
        <div class="box">
            <h4>Business Websites</h4>
            <p>Professional websites for shops, services, and companies.</p>
        </div>
        <div class="box">
            <h4>Portfolio Websites</h4>
            <p>Show your work as a designer, photographer, or freelancer.</p>
        </div>
        <div class="box">
            <h4>Landing Pages</h4>
            <p>Single-page sites focused on getting customers or sales.</p>
        </div>
    </div>
</section>

<section id="pricing" class="section">
    <h3>Pricing Plans</h3>
    <div class="pricing-boxes">
        <div class="box">
            <h4>Starter Website</h4>
            <p class="price">₹1,000</p>
            <p>1–3 pages<br>Mobile friendly<br>Basic design<br>Email support</p>
        </div>
        <div class="box">
            <h4>Business Website</h4>
            <p class="price">₹1,599</p>
            <p>Up to 6 pages<br>Modern design<br>Contact form<br>SEO basics</p>
        </div>
        <div class="box">
            <h4>Premium Website</h4>
            <
