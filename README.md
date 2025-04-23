# Ex04 Places Around Me
## Date: 23-04-2025

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
            <font color="red"><b>ERODE</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>HARSHIDA K S (212224040108) </b></font>
        </h3>
        <center>
            <img src="web map.png" usemap="#MyCity" height="610" width="1450">
            <map name="MyCity">
                <area shape="poly" coords="823,201,958,203,957,281,832,283" title="movie" href="movie.html">
                <area shape="poly" coords="595,73,726,68,730,163,608,163" title="mall" href="mall.html">
                <area shape="poly" coords="840,386,966,368,977,475,829,500" title="hotel" href="hotel.html">
    
            </map>
        </center>  
    </body>
</html>

mall.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ERODE</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>D-MART MALL</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="dmart.webp" alt="" height="400" width="600">
        <img src="dmart.webp" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                
                DMart has established a store in Erode, Tamil Nadu, offering a wide range of products and amenities to cater to the local community's shopping needs.
                
            </font>
        </p>
    </body>
</html>

hotel.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ERODE</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>Hotel Atrium</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="hotel.jpg" alt="" height="400" width="600">
        <img src="food.jpg" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                
                Hotel Atrium is a well-established 3-star hotel located on EVN Road in Erode, just a short distance from the railway station, making it an ideal choice for both business and leisure travelers. The hotel offers a range of modern amenities, including complimentary Wi-Fi, 24-hour room service, and a well-equipped conference hall. Guests can choose from various room types such as Club Rooms, Family Rooms, Patio Rooms, and the luxurious Presidential Suite—all designed with comfort in mind and equipped with features like LCD TVs, minibars, and rainfall showers. The hotel also houses a multi-cuisine restaurant that serves Indian, Chinese, and Mughlai dishes, along with a stylish bar called Illusion.
                
            </font>
        </p>
    </body>
</html>

movie.html

<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>ERODE</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>Annapoorani Theatre</b></font>
        </h2>
        <br>
        <hr size="3" color="yellow">
        <br>
        <center><img src="cinima theatre.png" alt="" height="400" width="600">
        <img src="cinima theatre.png" alt="" height="400" width="600"></center>
        <p align="justify">
            <font face="Georgia" size="5" color="black">
                Annapoorani Theatre, also known as A Square Cinemas Annapoorani, is a prominent single-screen cinema hall located in Vairapalayam, Erode, Tamil Nadu. Established in 1999, it has undergone significant renovations to enhance the movie-watching experience. The theatre now boasts modern amenities, including Dolby 7.1 surround sound and Sony 4K projection, providing an immersive cinematic experience. ​  
            </font>
        </p>
    </body>
</html>

```


## OUTPUT

map
![alt text](<map op.png>)

mall
![alt text](<mall op.png>)

hotel
![alt text](<hotel op.png>)

movie
![alt text](<movie op.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
