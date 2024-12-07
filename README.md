# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
image map.html
```
<html>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet"> 
        <title>Image map</title>
        <style>
            #head h1{
                position: absolute;
                top: 0px;
                left: 570px;
                font-family:  "Pacifico", cursive;
                font-size: 75px;
            }
            #map img{
                position: absolute;
                top: 200px;
                left: 60px;
            }
            #space{
                top: 1000px;
                position: absolute;
                width: 1500px;
                height: 100px;
            }
        </style>
    </head>
<!---{% load static %}-->
    <body>
        <div id="head">
            <h1>Pondi Mapzz</h1>
        </div>

        <div id="map">
            <!--<img src="{%static 'the image in the static'}-->"
            <img src="C:\PRIVATE\Web Application Development\Images\image.png" usemap="#image-map">
            <map name="image-map">
                <area target="" alt="" title="" href="Cricket academy image map.html" coords="96,552,133,555,134,623,90,628,81,590,147,590" shape="poly">
                <area target="" alt="" title="" href="Gym.html" coords="255,943,290,941,308,970,288,1018,244,985" shape="poly">
                <area target="" alt="" title="" href="Agency.html" coords="1652,914,684,911,695,949,655,957,676,964" shape="poly">
            </map>
        </div>
        <div id="space">
        </div>
    </body>
</html>
```
Cricket academy image map.html
```
<html>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bokor&family=Pacifico&display=swap" rel="stylesheet">
        <title>Smashers Cricket Academy</title>
        <style>
            body{
               background-image: url(menu\ bg.jpg);
            }
            #head h2{
                position: absolute;
                background-color: rgb(210, 29, 29);
                top: 40px;
                width:1510px;
                height: 80px;
                font-size: 60px;
                text-align: center;

            }
            #logo img{
                position: absolute;
                left: 550px;
                top: 230px;    
            }
            #logo2 img{
                position:absolute;
                left: 130px;
                top:230px;    
            }
            #about h1{
                position: absolute;
                top: 550px;
                left: 100px;
                font-size: 45px;
            }
            #about p{
                position: absolute;
                top: 600px;
                left: 200px;
                font-size: 40px;
                line-height: 55px;
                word-spacing: 10px;

            }
        </style>
    </head>
    <body>
        <div id="logo">
            <img src="C:\PRIVATE\Web Application Development\Images\cricket.jpg" height="300px" width="700px">
        </div>
        <div id="logo2">
            <img src="C:\PRIVATE\Web Application Development\Images\cricket player logo.avif" height="300px">
        </div>
        <div id="head">
            <h2>Smashers Cricket Academy</h2>
        </div>
        <div id="about">
            <h1>About Us :</h1>
            <p>This cricket academy is a specialized training center designed to develop the skills of aspiring cricketers. It provides structured coaching programs tailored for different age groups and skill levels, from beginners to advanced players. These academies focus on honing batting, bowling, fielding, and fitness through professional coaches and modern facilities. Players are often taught both technical aspects of the game and strategic thinking</p>
        </div>
        </body>
</html>
```
Agency
```
<html>
    <head>
        <title>AST Agenices</title>
        <style>
            body{
                background-image: url(agency\ bg.avif);
            }
            #logo img{
                position: relative;
                left: 570px;
                top: 0px;    
            }
            #about h1{
                position: absolute;
                top: 300px;
                left: 100px;
                font-size: 45px;
            }
            #about p{
                position: absolute;
                top: 350px;
                left: 200px;
                font-size: 40px;
                line-height: 55px;
                word-spacing: 10px;
            }
        </style>
    </head>
    <body>
        <div id="logo">
            <img src="C:\PRIVATE\Web Application Development\Images\water.webp" width="400px">
        </div>

        </div>
        <div id="about">
            <h1>About Us :</h1>
            <p>This water can agency supplies clean, potable drinking water to households, offices, and commercial establishments in the form of bottled or large water cans. They source water from purified and treated facilities, ensuring that it meets health and safety standards. The agency typically offers a subscription or on-demand delivery service, making it convenient for customers to receive water directly to their doorstep. Water can agencies often provide various container sizes, ranging from smaller bottles to 20-liter cans, depending on customer needs. Regular quality checks and timely delivery are essential aspects of their service.</p>
    </body>
</html>
```
# OUTPUT
![imagess](https://github.com/user-attachments/assets/d0cdc248-5fba-4862-a4c8-4fd453415d9c)

![Screenshot 2024-12-08 001006](https://github.com/user-attachments/assets/32ae83ce-dfed-4ea7-a7fe-3707848e261f)

![image (2)](https://github.com/user-attachments/assets/0f91a417-0b0c-4dbf-94f0-76368a68614a)

# RESULT
The program for implementing image maps using HTML is executed successfully.
