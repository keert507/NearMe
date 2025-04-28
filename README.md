# Ex04 Places Around Me
## Date: 25/4/2025

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


<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body bgcolor="#fdfaf6" text="#2c2c2c">

    <h1 align="center">
        <font color="#4B0082" size="10" face="Georgia">CHENNAI</font>
    </h1>

    <h3 align="center">
        <font color="#800000" size="6" face="Trebuchet MS">KEERTHANA T (212224100031)</font>
    </h3>

    <center>
        <img src="map.png" usemap="#MyCity" height="610" width="1450">
        <map name="MyCity">
            <area target="" alt="Government Museum Chennai" title="Government Museum Chennai" href="Museum.html" coords="542,86,669,164" shape="rect">
            <area target="" alt="Express Avenue" title="Express Avenue" href="eavenue.html" coords="648,285,771,351" shape="rect">
            <area target="" alt="Chidambaram Stadium" title="Chidambaram Stadium" href="stadium.html" coords="1085,215,1297,291" shape="rect">
            <area target="" alt="PVR" title="PVR" href="pvr.html" coords="476,345,643,407" shape="rect">
            <area target="" alt="AGS" title="AGS" href="ags.html" coords="306,530,490,556" shape="rect">
        </map>
    </center>

</body>
</html>



museum.html


<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">Museum Chennai</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            Chennai is home to several renowned museums that showcase its rich history and culture. 
            The Government Museum in Egmore, one of India s oldest, houses archaeological and art collections. 
            Fort Museum highlights Chennai s colonial past with British-era artifacts. 
            DakshinaChitra displays traditional South Indian homes and heritage. 
            The Chennai Rail Museum offers insights into India  s railway history with vintage locomotives and exhibits.
        </font>
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>



eavenue.html


<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">Express Avenue</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            Express Avenue is a large shopping mall located in Royapettah, Chennai.  
            It features over 210 retail stores, including top international brands.  
            The mall has a spacious food court called EA Garden and an 8-screen Escape Cinema.  
            It also includes South India's largest gaming arcade.  
            Open daily from 10 AM to 10 PM, it offers ample parking and modern amenities.
        </font>
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>



stadium.html


<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">M. A. Chidambaram Stadium </font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            Chepauk Stadium, officially called M. A. Chidambaram Stadium, is in Chennai.
            It was established in 1916 and is one of India s oldest cricket grounds.
            The stadium can seat around 38,000 spectators.
            It is the home ground of the Chennai Super Kings (CSK) in the IPL.
            Chepauk is known for historic matches, including India's first Test win in 1952.
        </font>
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>


pvr.html

<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">PVR Sathyam Cinemas</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            PVR Sathyam Cinemas is a popular multiplex located in Royapettah, Chennai.
            It was originally known as Sathyam Cinemas before being acquired by PVR in 2018.
            The theatre is known for its comfortable seating and high-quality sound system.
            It offers a great movie experience along with popular snacks like popcorn and cold coffee.
            Movie tickets and showtimes are available on platforms like BookMyShow.
        </font>
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>



ags.html


<!DOCTYPE html>
<html>
<head>
    <title>CHENNAI CITY</title>
</head>
<body bgcolor="#fefcf9" text="#2c2c2c">

    <h1 align="center">
        <font size="10">CHENNAI</font>
    </h1>

    <h2 align="center">
        <font size="7">AGS Cinemas</font>
    </h2>

    <hr size="5" width="80%" color="#003366">

    <p align="center">
        <font face="Georgia" size="6">
            AGS Cinemas T. Nagar is a modern multiplex located on G.N. Chetty Road, Chennai.
            It features 4 screens with a total seating capacity of 892.
            The theatre offers a comfortable movie experience with food and beverage options.
            It supports m-ticketing and has parking facilities for visitors.
            Tickets and showtimes are available on the AGS website and BookMyShow.
        </font>
    </p>

    <hr size="3" width="60%" color="#800020">

</body>
</html>


```

## OUTPUT
![Screenshot 2025-04-28 190357](https://github.com/user-attachments/assets/6e879ca6-090a-4463-98d3-a23a80866915)

![image](https://github.com/user-attachments/assets/20de3b57-282c-4017-a191-c3a43a4e16c8)

![image](https://github.com/user-attachments/assets/2eb059a2-0562-46b7-8c8e-b2f67f072d02)

![image](https://github.com/user-attachments/assets/af0c8b13-5103-4629-9c7f-8c479e36d5db)

![image](https://github.com/user-attachments/assets/12a00251-13f8-4441-83fb-6425dbc2e5aa)

![image](https://github.com/user-attachments/assets/baff5083-2654-4c0d-a98f-c6a64f1c6bc3)

![image](https://github.com/user-attachments/assets/37fda8e2-c121-44fa-876b-4ff1f835bbee)



## RESULT
The program for implementing image maps using HTML is executed successfully.
