# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
<title>Book Cover</title>
<style>
body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    font-family: georgia;
    background-color: #000;
}

.container {
    width: 700px;
    height: 950px;
    border: 8px solid #0C1E3A;
    padding: 30px;
    position: relative;
    box-sizing: border-box;
    background: url('download.jpg') no-repeat center center;
    background-size: cover;
}

.big-title {
    text-align: center;
    margin-top: 40px; /* reduced from 70px to move up */
    font-size: 45px;
    font-weight: bold;
    color: #248cc8;
    font-family: 'Times New Roman', serif;
    text-shadow: 2px 2px 10px #000;
}

.sub {
    text-align: center;
    margin-top: 15px;
    font-size: 22px;
    color: #248cc8;
    font-style: italic;
    text-shadow: 1px 1px 8px #000;
}

.author-img {
    position: absolute;
    bottom: 160px;
    right: 60px;
    width: 130px;
    height: auto;
    border-radius: 5px;
    box-shadow: 0 0 18px rgba(0,0,0,0.7);
}

.author-left {
    position: absolute;
    bottom: 90px;
    left: 50px;
    font-size: 26px;
    font-weight: bold;
    color: #248cc8;
    text-shadow: 1px 1px 8px #000;
}

hr {
    width: 60%;
    margin-left: 0;
}
</style>
</head>
<body>
<div class="container">
    <div class="big-title">HARRY POTTER<br>AND THE GOBLET OF FIRE</div>
    <div class="sub">A Tale of Magic and the Triwizard Tournament</div>
    <div class="author-left">J.K. Rowling</div>
    <img src="jk.png" class="author-img" alt="Author Image">
</div>
</body>
</html>
```



## OUTPUT:
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/633ad973-e1e7-4cc8-8295-5c05f1cb9e7e" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
