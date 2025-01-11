<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Your Business Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }

        header {
            background-color: #8B0000; /* Dark red color */
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #B22222; /* Lighter red */
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 15px;
            font-size: 1.2em;
        }

        nav a:hover {
            background-color: #8B0000; /* Dark red on hover */
            border-radius: 5px;
        }

        .main-content {
            padding: 40px 20px;
            text-align: center;
        }

        .section {
            padding: 40px 20px;
            text-align: left;
        }

        .section h2 {
            font-size: 2em;
            color: #8B0000;
        }

        footer {
            background-color: #8B0000;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        /* Contact Form Styling */
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }

        .contact-form button {
            background-color: #B22222;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #8B0000;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Business Name</h1>
        <p>Welcome to our professional website</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="main-content">
        <h2>Our Business Services</h2>
        <p>We provide high-quality services to meet your business needs. Get in touch with us today!</p>
    </div>

    <!-- About Us Section -->
    <div class="section" id="about">
        <h2>About Us</h2>
        <p>We are a passionate team dedicated to providing the best solutions for your business. Our expertise spans various industries, and we take pride in delivering tailored services to meet our clients' needs.</p>
    </div>

    <!-- Services Section -->
    <div class="section" id="services">
        <h2>Our Services</h2>
        <ul>
            <li><strong>Consulting:</strong> Professional consulting services to optimize your business operations.</li>
            <li><strong>Web Development:</strong> Custom web development solutions to help you grow online.</li>
            <li><strong>Marketing:</strong> Strategic marketing services to boost your brand visibility.</li>
            <li><strong>Design:</strong> Creative design services for your branding and marketing materials.</li>
        </ul>
    </div>

    <!-- Contact Us Section -->
    <div class="section" id="contact">
        <h2>Contact Us</h2>
        <p>Have any questions or inquiries? Feel free to reach out to us using the contact form below:</p>
        
        <form class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>

    <footer>
        <p>&copy; 2025 Your Business Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
