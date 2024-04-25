# Ex.06 Book Front Cover Page Design
## Date:5.3.24

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
        <title>
            book front page
        </title>
        <style>
            .bookpage{
                background-image: url(backgroundimage.png);
                height: 600px;
                width: 300px;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                background-size: cover;
                
            }
            .scoft{
                color: black;
                font-size: medium;
            }
            
            .subtopic{
                color: rgb(188, 235, 188);
                font-size: small;
                font: bold;
            }
            .mypic{
                 position: relative;
                 width: 80px;
                 height: 90px;
                 top: 200px;
                 left: 200px;
                 background-size: contain;
            }
            .hrtg{
                position: relative;
                top: 250px;
            }
            .ed{
                color:aliceblue;
                top: 200px;
                position: relative;
                font-size: medium;
            }
            .author{
                position: relative;
                top: 210px;
                color:aliceblue;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            }
            .sec{
                position: relative;
                top: 170px;
                left: 235px;
                color:aliceblue;
            }


        </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="scoft">
                SCOFT</div>
            <div class="hrtag"><hr style="color:azure"></div>
            <div class="topic"> 
                <h1 style="color: aliceblue">INFORMATION TECHNOLOGY</h1>
            </div>
            <div class="subtopic"> 
                <h3>This field will induced an interest and will give a create innovation ideas</h3></div>
           <div class="subtitle">
            
           </div>
           <div class="mypic">
            <img src="mypic.jpg" width="90" height="130">
           </div>
           <div class="hrtg">
               <hr style="color: aliceblue;">
           </div>
           <div class="ed">
            <h3>SPECIAL EDITION</h3>
           </div>
           <div class="author">
                <h3> Nithish Kumar B</h3>
           </div>
           <div class="sec">
               <h3>SEC</h3>
           </div>
        </div>
 </body>
</html>

```

## OUTPUT:
![WhatsApp Image 2024-04-25 at 9 04 30 PM](https://github.com/Nithish7105/cover/assets/149516932/2e2af53d-3326-41d9-aeb0-695b6001fb6d)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
