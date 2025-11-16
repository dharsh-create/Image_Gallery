# Ex.08 Design of Interactive Image Gallery

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>My Gallery</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

<h1>My Photo Gallery</h1>

<div class="main-box">
    <img id="main-image" src="images/img1.jpg" alt="Main Image">
</div>

<div class="thumbnail-box">
    <img src="images/img1.jpeg" class="thumb" onclick="changeImage('images/img1.jpeg')">
    <img src="images/img2.jpeg" class="thumb" onclick="changeImage('images/img2.jpeg')">
    <img src="images/img3.jpeg" class="thumb" onclick="changeImage('images/img3.jpeg')">
    <img src="images/img4.jpeg" class="thumb" onclick="changeImage('images/img4.jpeg')">
    <img src="images/img5.jpeg" class="thumb" onclick="changeImage('images/img5.jpeg')">
    <img src="images/img6.jpeg" class="thumb" onclick="changeImage('images/img6.jpeg')">
</div>

<script src="js/script.js"></script>
</body>
</html>

body {
    font-family: Arial;
    text-align: center;
    background: #f4f4f4;
}

.main-box img {
    width: 400px;
    height: auto;
    border: 3px solid black;
    margin-bottom: 20px;
}

.thumbnail-box {
    display: flex;
    justify-content: center;
    gap: 10px;
}

.thumbnail-box img {
    width: 100px;
    cursor: pointer;
    border: 2px solid gray;
}
function changeImage(imagePath) {
    document.getElementById("main-image").src = imagePath;
}
```

## OUTPUT
<img width="1916" height="1019" alt="Screenshot 2025-11-16 112426" src="https://github.com/user-attachments/assets/6b765679-4264-41ed-984f-0a939ca09ecd" />

## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
