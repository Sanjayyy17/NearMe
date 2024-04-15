# Ex04 Places Around Me
## Date: 15-04-24

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
findapp.html

<html>
    <head>
        <title>CHENNAI</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
    
        <font color="yellow">CHENNAI CITY</font>
        </h1>
        <h2 align="center"
        <font color="black">M S SANJAY</font>
    </h2>
    <h3 align="center">
    <font color="black">212223040183</font>
    </h3>

<img src="chennai.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="AMBATTUR" title="AMBATTUR" href="ambattur.html" coords="920,434,1051,551" shape="rect">
    <area target="" alt="Avadi" title="Avadi" href="avadi.html" coords="611,496,782,614" shape="rect">
    <area target="" alt="KOYAMBEDU" title="KOYAMBEDU" href="koyambedu.html" coords="1065,709,1266,798" shape="rect">
    <area target="" alt="Kannapuram" title="Kannapuram" href="kannapuram.html" coords="1285,325,1473,423" shape="rect">
    <area target="" alt="Veppambaattu" title="Veppambaattu" href="veppambaattu.html" coords="158,393,375,498" shape="rect">
</map>
</center>
</body>
</html>

veppambaattu.html

<html>
    <head>
        <title>Veppambattu</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>Veppambattu</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Veppampattu is one of the fastest developing suburban areas in Chennai City. It is Western part of the suburbs of the Metropolitan city Chennai in the Indian state of Tamil Nadu between Chennai and Arakkonam on the Chennai - Arakkonam railway line.
            </font>
        </p>
    </body>
</html>

kannapuram.html

<html>
    <head>
        <title>Kannapuram</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>Kannapuram</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Kannapuram is a neighbourhood of Chennai, Tamil Nadu, India. Located in the northern part of Chennai, it is also a taluk in Chennai District and a zone in Greater Chennai Corporation. It is located in between Perambur and Kodungaiyur. 
            </font>
        </p>
    </body>
</html>

koyambedu.html

<html>
    <head>
        <title>Koyambedu</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>Koyambedu</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Koyambedu is a neighbourhood in Chennai, India. Situated in the western part of Chennai city, the Koyambedu area has become a major hub of activity in Chennai after the inauguration of the Koyambedu market in 1996 and the Chennai Mofussil Bus Terminus (CMBT) in 2002. The area is active round the clock owing to the movement of people and goods through the day, with uninterrupted transport facilities such as long-route buses, autos, share autos, vegetable goods carriers and so forth.
            </font>
        </p>
    </body>
</html>

avadi.html

<html>
    <head>
        <title>Avadi</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>Avadi</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Avadi bus terminus is located very near to the Avadi railway station on the Chennai - Thiruvallur High Road (CTH road). The depot is situated beside the bus terminal. Avadi is well connected to various locations of Chennai as well as rural areas surrounding North-western and Western Chennai. The main service provider though is the state-owned Metropolitan Transport Corporation buses, TNSTC/SETC buses to Tirupathi, Nellore, Bangalore, Shengottai, Tirunelveli, Tuticorin operates from here & few private buses are also available.
            </font>
        </p>
    </body>
</html>

ambattur.html

<html>
    <head>
        <title>My Hometown</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">
            <font color="maroon"><b>CHENNAI</b></font>
        </h1>
        <h3 align="center">
            <font color="maroon"><b>Ambattur</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Ambattur is a northwestern neighbourhood of Chennai, India. It is located in Ambattur taluk of the Chennai District, surrounded by Avadi, Anna Nagar, Padi, Mogappair, Kallikuppam, Surapet, Korattur, Ayappakkam, Athipet and Thiruverkadu. It covers an area of 45 km2 (17 sq mi). The neighbourhood is served by Ambattur railway station of the Chennai Suburban Railway. 
            </font>
        </p>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (1).png>)
![alt text](<Screenshot (2).png>)
![alt text](<Screenshot (3).png>)
![alt text](<Screenshot (4).png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (6).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
