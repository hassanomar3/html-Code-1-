<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Berimbolo Security</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Berimbolo Security</h1>
        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Security Risk Assessments</li>
            <li>Alarm System Installation</li>
            <li>CCTV Camera Setup</li>
            <li>24/7 Monitoring</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" required>

            <label for="message">Message:</label>
            <textarea id="message" required></textarea>

            <button type="submit">Submit</button>
        </form>
        <p id="responseMessage"></p>
    </section>

    <footer>
        <p>&copy; 2025 Berimbolo Security. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
