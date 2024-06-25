# git-tuts 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <section id="contact-form">
        <form action="/submit-your-form-handler" method="POST">
            <div>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br>
            </div>
            <div>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br>
            </div>
            <div>
                <label for="location">Location:</label><br>
                <input type="text" id="location" name="location"><br>
            </div>
            <div>
                <label for="phone">Phone:</label><br>
                <input type="tel" id="phone" name="phone"><br>
            </div>
            <div>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br>
            </div>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>Connect with us:</p>
        <!-- Your social media links or additional contact information can go here -->
    </footer>
</body>
</html>
