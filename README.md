# Ex.06 Book Front Cover Page Design
## Date:25.11.2023

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
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Book Cover page</title>

    <style>
        body {
            background-size: 494px;
            background-image: url('bake.jpg');
            background-position:center;
            width: 400px;
            height: 650px;
            margin-left: auto;
            margin-right: auto;
            
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-repeat: no-repeat;
        }

        h1 {
            text-align: center;
            color: black;
        } 
        .imge > img {
            height: 250px;
            width: 250px;
            float: right;
        }.word{
            padding-top: 2cm;
            padding-left:1 ;
        }
        .iyal{
            padding-left: 8cm;
            margin: top 20px;;
        }
        .second-image{
            border: 5px solid #336699; /* Set the border width, style, and color */
            border-radius: 8px;
            border-color:orangered;
            float: left;
        }
         .last{
      text-align: left;
      padding-right:270px;
      padding-bottom: 40x;
      margin-bottom:100px;

    }
    </style>
</head>
<body>
    <div class="up">
        <h3 style="color: red;"><u>Sec Insight</u></h3>
    </div>
    <br>
    <br>

    <h1><b>Full Stack Development<br><br>
        For beginners</b></h1>
    <div class="imge">
        <img src="./cov5.webp"  alt="">
    </div>
    <div class="word">
        <h3>
            <ul> <li>Front end</li>
                <br>
                <li>Back end</li>
                <br>
                <li>Database</li>
            </ul>
        </h3>
    </div>
    <div class="iyal"><img class="second-image" src="./,...jpg" alt="" height="100" width="80" allign="right">

    </div>
    
    <div class="last"><h1>Iyalarasu</h1>
    </div>
</body>
</html>


'''


## OUTPUT:
![Alt text](<Screenshot (36).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
