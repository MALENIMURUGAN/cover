# Ex.06 Book Front Cover Page Design
## Date:30.11.2023

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
<html>

<head>
    <title>CODE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 750px;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 10px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url("covr.jpeg");
            background-size:cover;
        }
            
        
        .insight{
            color:darkgoldenrod;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:darkgoldenrod;
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:darkgoldenrod;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:darkgoldenrod;
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
        }
        .ed{
            color:darkgoldenrod;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
        
        }
        .subtitle{
            color:darkgoldenrod;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 275px;
            left: 320px;
            width: 70px;
            height: 80px;
            background-size:contain;
        }
    </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                Start From Trash
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>The Code:The Hidden Language Of The Computer Hardware and Software</h1></div>
            <div class="subtitle">
                 Book On Core Of The Computers,The Way They Run
            </div>
            <div class="subtitle">
                 Top seller of 2023
            </div>

            <div class="mypic">
                <img src="photo.jpg" height="70" width="80" >
            </div>
            <div class="id">
                <hr style="color:DarkMagenta">
            </div>
            <div class="author">
               <p><b>MALENI.M</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
</html>
```

## OUTPUT:

![Alt text](cover2.png)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
