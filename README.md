# Ex04 Places Around Me
## Date:16:4:2024 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
``` python

Developed by :SETHUPATHI.K
Register Number :212223040189
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            background-color: aqua;
        }
        
    </style>
</head>
<body>
    <img src="d2.png" alt="" height = "530" usemap = "#MapNew" onmousemove = "coordinate(event)">
    <map name="MapNew">
        <area shape="RECT" coords="214,177,240,204" href="https://www.careerindia.com/colleges/c-t-m-college-of-arts-and-science-chennai-tamil-nadu-cp2816/" alt="ctm college">
        <area shape="RECT" coords="339,211,367,246" href="https://www.sreesasthaarts.in/" alt="sree sasthaa">
        <area shape="rect" coords="221,296,230,319" href="https://dmice.ac.in/" alt="dmice">
        <area shape="rect" coords="40,213,64,239" href="https://www.apolloartsandsciencecollegechennai.ac.in/about.aspx" alt="apollo arts and science">
        <area shape="rect" coords="190,453,216,473" href="https://lakeviewlifecentre.org/" alt="lakeview">
    </map><br>
    
    
   
</body>
</html>
```
## OUTPUT
![map](https://github.com/sethu107/NearMe/assets/149347373/08412da9-04f6-4b72-b2fc-3741fc50e3ba)
![image](https://github.com/sethu107/NearMe/assets/149347373/f789e599-d589-44f1-8974-63be17e1bdc0)
![image](https://github.com/sethu107/NearMe/assets/149347373/e80dcf96-6b6c-4f4f-8329-05d58bb5bfc1)
![image](https://github.com/sethu107/NearMe/assets/149347373/c1b961e3-040d-4cbb-8eb0-a8478fcd168b)
![image](https://github.com/sethu107/NearMe/assets/149347373/d0ec4e0f-d0d8-4d9e-9235-666cdaae74a9)
![image](https://github.com/sethu107/NearMe/assets/149347373/51eafead-009f-445b-a69d-6dab995ae44a)




## RESULT
The program for implementing image maps using HTML is executed successfully.
