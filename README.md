1. Create the style.css file:

/* style.css */

/* Body styling */
body {
    font-family: 'Arial', sans-serif; /* Set font for the whole page */
    background-color: #f4f4f9; /* Light grey background */
    margin: 0; /* Remove default margin */
    padding: 0; /* Remove default padding */
}

/* Styling for the header */
#header {
    background-color: #4CAF50; /* Green background */
    color: white; /* White text */
    text-align: center; /* Center-align text */
    padding: 20px; /* Add padding inside */
    font-size: 2em; /* Increase font size */
}

/* Styling for paragraph with a class */
.content {
    color: #333; /* Dark grey text */
    margin: 20px; /* Add margin around paragraphs */
    padding: 10px; /* Add padding inside paragraph */
    background-color: white; /* White background */
    border: 1px solid #ddd; /* Light grey border */
    border-radius: 5px; /* Rounded corners */
}

/* Styling for an image */
img {
    width: 100%; /* Make image take full width */
    max-width: 600px; /* Limit maximum width */
    height: auto; /* Maintain aspect ratio */
    display: block; /* Remove unwanted space below image */
    margin: 20px auto; /* Center the image and add margin */
}

/* Styling links */
a {
    color: #4CAF50; /* Green color */
    text-decoration: none; /* Remove underline */
}

a:hover {
    color: #333; /* Darker color when hovering */
    text-decoration: underline; /* Underline when hovered */
}
2. Create the index.html file:
html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <!-- Link to external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header with ID selector -->
    <div id="header">
        Welcome to My Styled Page
    </div>

    <!-- Main content with class selector -->
    <div class="content">
        <p>This is a sample paragraph styled with a class.</p>
        <p>Using margin, padding, borders, and different font to create better spacing and layout.</p>
    </div>

    <!-- Image styled -->
    <img src="https://via.placeholder.com/600" alt="Sample Image">

    <!-- A link styled -->
    <p>For more information, visit <a href="https://www.example.com" target="_blank">Example Website</a>.</p>

</body>
</html>
