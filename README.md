# Contact Form Project

This is a simple contact form that collects full name, email, and message from users and submits the data to a Google Sheet.

## Project Structure

- `index.html`: The HTML file containing the form.
- `formScript.js`: The JavaScript file that handles form submission.
- `README.md`: This file, providing information about the project.

## Setup Instructions

### Step 1: Create the HTML Form

Create an `index.html` file with the following content:

```html
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
