<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Dael Group - Waste Management, Recycling, and Hygiene Services">
    <title>Dael Group</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header .logo h1 {
            margin: 0;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        nav ul li a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            background: url('hero-image.jpg') no-repeat center center/cover;
            color: #fff;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        .hero h2 {
            font-size: 2.5rem;
            margin: 0 0 10px;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        .btn {
            background: #007bff;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background: #0056b3;
        }

        /* Section Styles */
        section {
            padding: 20px;
            text-align: center;
        }
        #services .service-cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        #services .card {
            background: #f4f4f4;
            margin: 10px;
            padding: 20px;
            border-radius: 5px;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        #services .card h3 {
            margin-top: 0;
        }

        /* Contact Form */
        form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
        }
        form input, form textarea, form button {
            margin: 10px 0;
            padding: 10px;
            font-size: 1rem;
            width: 100%;
        }
        form button {
            background: #007bff;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        form button:hover {
            background: #0056b3;
        }

        /* Footer */
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <h1>Dael Group</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home">
        <div class="hero">
            <h2>Your Partner in Waste Management & Hygiene Services</h2>
            <p>Innovative solutions for a cleaner, sustainable future.</p>
            <a href="#contact" class="btn">Get a Quote</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>Our Services</h2>
        <div class="service-cards">
            <div class="card">
                <h3>Waste Management</h3>
                <p>Comprehensive solutions for waste collection, sorting, and disposal.</p>
            </div>
            <div class="card">
                <h3>Recycling</h3>
                <p>Transforming waste into valuable resources through advanced recycling methods.</p>
            </div>
            <div class="card">
                <h3>Hygiene Services</h3>
                <p>Professional cleaning and hygiene solutions for businesses and households.</p>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>Dael Group is a Black-owned company committed to providing sustainable waste management and hygiene solutions, creating jobs, and uplifting communities.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <input type="text" name="phone" placeholder="Your Phone" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
        <div class="contact-info">
            <p>Email: ziphathe.dael@dael-group.co.za</p>
            <p>Phone: +27 723 083 497</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Dael Group. All rights reserved.</p>
    </footer>
</body>
</html>
