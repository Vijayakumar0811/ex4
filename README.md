# Ex04 Places Around Me
## Date: 22-04-2025
NAME: VIJAYAKUMAR S

REG NO: 212224040359

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
```
map.html

<html>
<head>
<title>My City</title>
 </head>
 <body>
 <h1 align="center">
 <font color="red"><b>CHENNAI</b></font>
</h1>
<h3 align="center">
 <font color="blue"><b>VIJAYAKUMAR (212224040359)</b></font>
</h3>
 <center> 
<img src="map.png" usemap="#MyCity" height="895" width="1809">
<map name="MyCity">
    
    <area target="_blank" alt="Phoenix" title="Phoenix" href="Phoenix.html" coords="495,320,653,317,663,258,463,256,495,311,469,260" shape="poly">
    <area target="_blank" alt="IIT" title="IIT" href="iit.html" coords="1212,301,1208,432,1468,437,1462,298" shape="poly">        <area target="_blank" alt="Temple" title="Temple" href="temple.html" coords="944,555,914,589,941,621,1090,624,1149,602,1208,562" shape="poly">
    <area target="_blank" alt="Lake" title="Lake" href="lake.html" coords="132,495,162,521,244,525,829,602,471,444" shape="poly">
    <area target="_blank" alt="MY HOME" title="MY HOME" href="myhome.html" coords="535,872,33" shape="circle">
    
</map>
</center>
</body>
</html>

Phoenix.html

<html>
<head>

<title>My Home Town</title>

</head>

<body bgcolor="yellow">

<h1 align="center">

<font color="red"><b>CHENNAI</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>Phoenix</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Phoenix Marketcity Chennai, located in Velachery, is one of the largest shopping malls in the city, offering a mix of retail, dining, and entertainment experiences. Opened in January 2013, it spans 1 million square feet and houses over 250 stores, including global brands. The mall features Chennai’s first IMAX screen, a gaming arcade, and a variety of restaurants, making it a popular destination for shopping and leisure.


</p>

</body>

</html>

iit.html

<html>
<head>

<title>My Home Town</title>

</head>

<body bgcolor="palegreen">

<h1 align="center">

<font color="red"><b>CHENNAI</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>Indian Institute of Technology</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">

    IIT Madras, located in Chennai, is one of India's premier engineering institutions, established in 1959. It offers cutting-edge research facilities and a wide range of undergraduate and postgraduate programs across various disciplines. The campus is known for its lush greenery, advanced labs, and strong industry collaborations, making it a hub for innovation and technology.

</p>

</body>

</html>


lake.html

<html>

<head>

<title>My Home Town</title>

</head>

<body bgcolor="pink">

<h1 align="center">

<font color="red"><b>CHENNAI</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>Velachery Lake</b></font>

</h3>

<hr size="3" color="red">

<p align="justify">

<font face="Georgia" size="5">
    Velachery Lake, located in Chennai, is a vital waterbody that helps manage monsoon runoff and supports groundwater recharge. Over the years, rapid urbanization has led to significant encroachment, reducing its original size from 265 acres to just 55 acres. Efforts have been proposed to restore and beautify the lake, including fencing, walking decks, and plantation projects.


</p>

</body>

</html>
```

## OUTPUT

![Screenshot 2025-04-22 122333](https://github.com/user-attachments/assets/02d28c89-5dfe-4627-930d-6028026d2c92)

![Screenshot 2025-04-22 134836](https://github.com/user-attachments/assets/9ce31311-ddaf-41b9-b055-993782a08dd2)

![Screenshot 2025-04-22 134709](https://github.com/user-attachments/assets/454e872b-f92d-44c0-9201-c7abfd179dbc)

![Screenshot 2025-04-22 134719](https://github.com/user-attachments/assets/efe5d68b-a013-4b6c-8d78-40a1cccfd469)



## RESULT
The program for implementing image maps using HTML is executed successfully.
