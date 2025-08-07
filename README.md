<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us -  Travel</title>
</head>
<body>
    <h1>Contact ExploreEase Travel</h1>
    <p>We’d love to hear from you! Whether you're looking for help planning your trip, need support, or just want to say hello — we’re here to help.</p>

    <form action="/contact/" method="post">
       
        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name" required placeholder="Your full name"><br><br>

        <label for="email">Email Address:</label><br>
        <input type="email" id="email" name="email" required placeholder="you@example.com"><br><br>

        <label for="phone">Phone Number (optional):</label><br>
        <input type="tel" id="phone" name="phone" placeholder="+92 300 1234567"><br><br>

        <label for="subject">Subject:</label><br>
        <input type="text" id="subject" name="subject" placeholder="e.g., Help with booking"><br><br>

        <label for="message">Your Message:</label><br>
        <textarea id="message" name="message" rows="6" required placeholder="Write your question, feedback, or request here..."></textarea><br><br>

        <button type="submit">Send Message</button>
    </form>

    <footer>
        <p><strong>ExploreEase Travel</strong></p>
        <p>📍 Head Office: Main Boulevard, Lahore, Pakistan</p>
        <p>📞 +92 300 1234567 &nbsp;&nbsp; ✉️ contact@exploreease.com</p>
    </footer>
</body>
</html>
