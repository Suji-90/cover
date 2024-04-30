# Ex.06 Book Front Cover Page Design
## Date:30.04.2024

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
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgba(246, 245, 247, 0.896);
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(bookcover.jpeg) ;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(148, 109, 54);
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(167, 78, 27);
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(150, 82, 18);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: rgb(187, 193, 19);
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: rgb(100, 175, 20);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:brown(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: rgb(169, 158, 16);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>CODER</b>
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(117, 152, 27)">
            </div>
            <div class="booktitle">
                <h1><b>Machine Learning Mastery</b></h1></div>
            <div class="subtitle">
                 <b> </b> 
            <div class="subtitle2">
                <b>>> Import existing software applications</b><br>
                <b>>> Data structure and algorithms</b><br>
                <b>>> Software Quality</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="pic.jpeg" width="90" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(207, 21, 157)">
            </div>
            <div class="author">
               <p><b> SUJITHRA.K(212223040212)</b></p>
            </div>
            <div class="pub">
                SEC 27'
            </div>
        </div>
    </div>
</body>
</html>

```

## OUTPUT:
![Screenshot (5)](https://github.com/Suji-90/cover/assets/150884148/74c30371-55a6-407d-8920-3295f461de20)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
