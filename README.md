# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
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


<!DOCTYPE html>
<html lang="en">
<head>
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"
     
</head>
<body>
    <header id="main-header">Welcome to My Styled Page</header>
    
   <p class="text-content">This is a sample paragraph styled using a class. It has padding, margins, and a border to make it more readable.</p>

   <img src="example.jpg" alt="Sample Image" class="image-style">
</body>
</html>


body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}


#main-header {
    background-color: #007bff;
    color: white;
    text-align: center;
    padding: 20px;
    font-size: 24px;
    border-bottom: 5px solid #0056b3;
}


.text-content {
    font-size: 18px;
    line-height: 1.6;
    margin: 20px;
    padding: 10px;
    background-color: #ffffff;
    border-left: 5px solid #007bff;
}


.image-style {
    display: block;
    width: 300px;
    height: auto;
    margin: 20px auto;
    border: 5px solid #007bff;
    border-radius: 10px;
}

