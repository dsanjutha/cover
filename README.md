# Ex.06 Book Front Cover Page Design
## Date:07.10.2025

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
book.html
<html>
    <head>
        <title>Book Cover Page</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="bookcover">
        <div class="margin">
        <div class="insight">
            SEC Insights
        </div>
        <div class="hrstyle">
            <hr style="color: pink">
        </div>
        <div class="title">
            <h1>information<br>technology<br>essentials</h1></div>
        <div class="subtitle">
            top innovation and trends in 2025
        </div>
        <div class="subtitle">
            Rare celestial phenomena in 2025
        </div>
        <div class="mypic">
            <img src="author.png" width="100" height="120">
        </div>
        <div class="id">
            <hr style="color: pink">
        </div>
        <div class="author">
            <p><b>d sanjutha</b></p>
        </div>
        <div class="publisher">
            SEC
        </div>
        <div class="edition">
            Special Edition
        </div>
        </div>
        </div>
    </body>
</html>

style.css
.bookcover{
    width: 400px;
    height: 600px;
    color: blue;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(cover.png);
    background-size: cover;
}

.margin{
    width: 400px;
    height: 600px;
	border: solid 2px pink;
	background-size: cover;
}
        
.insight{
    color: pink;
    left: 5px;
    top: 8px;
    position: relative;
}
        
.hrstyle{
    width: 95px;
	height: 2px;
    color: pink;
}

.title{
    color: pink;
    font-family: Verdana;
    font-size: x-large;
    text-align: center;
    position: relative;
    top: 25px;      
}

.subtitle{
    color: pink;
    font-family: Tahoma;
    font-size: medium;
    position: relative;
    left: 13px;
    top: 20px;
}

.mypic{
    position: relative;
    top: 110px;
    left: 290px;
    width: 75px;
    height: 80px;
    background-size:contain;
        }

.id{
    width:400px;
    height: 2px;
    position: relative;
    top:150px;
}

.author{
    display: inline;
    position: relative;
    color: pink;
    top:135px; 
    left: 8px;           
    font-family: Times New Roman;
    font-size: medium;
}
        
.publisher{
    color: pink;
    font-size: medium;
    position: relative;
    font-family:Times New Roman;
    top:100px;
    left:360px;
}

.edition{
    color: pink;
    font-size: medium;
    font-family:Times New Roman;
    position: relative;
    left: 8px;
    top:60px;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-10-07 194436.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
