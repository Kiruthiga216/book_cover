# Ex.06 Book Front Cover Page Design
# Name:KIRUTHIGA.B
# REG.NO:212224040160
# Date:12/104/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Front cover page
        </title>
        <style>
            .bookpage{
                height:700px;
                width:600px;
                margin-left:30%;
                background-image: url("bg.png");
                padding:10px;
                background-size: cover;
                align:center;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 30px;
                color:black;
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:black;
                font-size: large;
            }
            
            .mypic{
                position: relative;
                top:90px;
                left:470px;
                height: 100px;
                width: 70px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            .ed{
                position:relative;
                top: 80px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
            }
            .pb{
                position: relative;
                left:420px;
                top:-50px;
                font-size: x-large;
            }
        </style>
        <body>
            <div class="bookpage">
            <div style="color:rgb(191, 16, 200)">INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h1>Conversation Of Nature</h1></div>
            <div class="subtitle">Protecting Our Planet, Preserving Our Future.---</div>
            <div class="mypic"><img src="Screenshot 2025-04-12 152326.png" width="120px" height="140px" ></div>
            <div class="ed" style="color: bisque;">SPECIAL EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author">
            <div style="color:wheat" >KIRUTHIGA.B</div>
            <div class="pb" style="color:wheat"> <h3>SEC</h3></div>
        </div>
        </body>
    </head>
</html>

```
# OUTPUT:

![alt text](<Screenshot 2025-04-12 160848.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
