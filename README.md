<!DOCTYPE html>
<html>
<head>
    <title>Contact Form</title>
</head>
<body>
    <h2>Contact Form</h2>
    <form id="contactForm">
        <label for="fullName">Full Name:</label><br>
        <input type="text" id="fullName" name="fullName" required><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" required></textarea><br><br>
        <input type="submit" value="Submit">
    </form>
    <script src="formScript.js"></script>
</body>
</html>

