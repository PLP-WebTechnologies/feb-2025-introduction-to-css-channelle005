# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file

/* style.css */

/* General Body Style */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

/* Header Style */
#header {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
    text-align: center;
}

/* Main Content */
.main-content {
    margin: 30px;
    padding: 20px;
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 5px;
}

/* Paragraph inside main content */
.main-content p {
    color: #333;
    font-size: 16px;
    line-height: 1.5;
}

/* Button Style */
.button {
    background-color: #008CBA;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    text-align: center;
    font-size: 16px;
}

.button:hover {
    background-color: #005f73;
}

/* Footer Style */
#footer {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
    position: fixed;
    width: 100%;
    bottom: 0;
}

Apply CSS to a HTML page.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header Section with ID -->
    <div id="header">
        <h1>Welcome to My Styled Page</h1>
    </div>

    <!-- Main Content Section with Class -->
    <div class="main-content">
        <h2>This is a heading inside the main content area</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque, nisi id ultricies pretium, elit leo varius felis, nec varius lorem eros eget risus. Integer ut nisl id libero lacinia vehicula.</p>
        <button class="button">Click Me</button>
    </div>

    <!-- Footer Section with ID -->
    <div id="footer">
        <p>Footer content goes here.</p>
    </div>

</body>
</html>

Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
