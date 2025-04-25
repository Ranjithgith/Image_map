# Ex04 Places Around Me
# Date:12/04/2025
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

# CODE:
# map.html:
```html>
    <head>
        <title>My City</title>
        <style>
            .imagecenter{
                display: block;
                margin-left: auto;
                margin-right: auto;
            }
        </style>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Madurai</b></font>
          </h1>
          <h3 align="center">
              <font color="blue"><b>Ranjith.R (24901221)</b></font>
          </h3>
          <img src="map.png" usemap="#image-map" class="imagecenter">

          <map name="image-map">
              <area target="" alt="" title="" href="park.html" coords="869,222,605,47" shape="0">
              <area target="" alt="" title="" href="goripal.html" coords="1279,336,1244,351" shape="0">
              <area target="" alt="" title="" href="hill.html" coords="761,719,923,745" shape="0">
              <area target="" alt="" title="" href="museum.html" coords="1530,832,1650,856" shape="0">
              <area target="" alt="" title="" href="place.html" coords="1320,452,1418,414"  shape="0">

          </map>
        </map>
    </body>
</html>
```
# place.html:
```<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="blue">

        <h1 align="center">
          <font color="red"><b>Madurai</b></font>
        </h1>
        <h3 align="center">
            <font color="yellow"><b>Anna Nagar</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Anna Nagar in Madurai is a well-developed residential and commercial area known for its organized layout and good connectivity to key parts of the city. It offers a range of amenities including schools, hospitals, and shopping centers. The locality is popular for both homebuyers and renters, with properties catering to various budgets. Though it can experience traffic congestion, it remains a vibrant and convenient neighborhood.
        </font>
        </p>
     </body>
 </html>
```
# musuem.html:
```<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="red">

        <h1 align="center">
          <font color="white"><b>Madurai</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>Keeladi Museum</b></font>
        </h3>
        <hr size="5" color="black">
        <p align="justify">
        <font face="Georgia" size="5">
            The Keeladi Heritage Museum, located near Madurai in Tamil Nadu, showcases artifacts from the ancient Sangam-era civilization, including pottery, tools, and inscriptions dating back over 2,000 years. Inaugurated in March 2023, the museum spans 31,000 square feet and features exhibits that provide insights into early Tamil society and culture. Visitors can explore reconstructed huts, virtual reality experiences of the excavations, and models of Sangam-era ships. The museum is open from 10 AM to 6 PM, closed on Tuesdays and national holidays, with an entrance fee of ₹15 for adults.​
        </font>
        </p>
     </body>
 </html>
```
# park.html:
```
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="yellow">

        <h1 align="center">
          <font color="red"><b>Madurai</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Athisayam Theme Park</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Athisayam Theme Park, located near Madurai in Tamil Nadu, is a 70-acre amusement and water park offering a wide range of rides and attractions for all ages. Highlights include the 70-foot artificial waterfall "Madurai Courtallam," thrilling water slides, roller coasters, and family-friendly play zones. It also features a 7D theater, food courts, and recreation areas. The park is open daily from 10 AM to 6:30 PM.
        </font>
        </p>
     </body>
 </html>
```
# hill.html:
```<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="yellow">

        <h1 align="center">
          <font color="red"><b>Madurai</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Athisayam Theme Park</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Athisayam Theme Park, located near Madurai in Tamil Nadu, is a 70-acre amusement and water park offering a wide range of rides and attractions for all ages. Highlights include the 70-foot artificial waterfall "Madurai Courtallam," thrilling water slides, roller coasters, and family-friendly play zones. It also features a 7D theater, food courts, and recreation areas. The park is open daily from 10 AM to 6:30 PM.
        </font>
        </p>
     </body>
 </html>
```
# goripal.html:
```<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="white">

        <h1 align="center">
          <font color="red"><b>Madurai</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Goripalayam</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
        <font face="Georgia" size="5">
            Goripalayam is a prominent area in Madurai, Tamil Nadu, known for its historical and cultural significance. The centerpiece is the Goripalayam Dargah, a famous Islamic shrine housing the tombs of two Sultans from Yemen. The Dargah's massive dome is one of the largest in South India, carved from a single block of stone. Besides its religious importance, Goripalayam is also a busy commercial hub and a key landmark in the city.
        </font>
        </p>
     </body>
 </html>
```


# OUTPUT:
# map:
![Screenshot 2025-04-14 153529](https://github.com/user-attachments/assets/0c719642-dba4-4d88-9dda-78e3ed0f5da2)
# park:

![Screenshot 2025-04-14 152256](https://github.com/user-attachments/assets/e15a7106-6a9a-4f20-8478-52f0ffb94cda)

# hill:
![Screenshot 2025-04-14 153037](https://github.com/user-attachments/assets/c3d9f35b-0fc0-4d41-810a-343198c1a627)

# goripal:
![Screenshot 2025-04-14 153323](https://github.com/user-attachments/assets/75ccf15b-c917-4648-96fa-78f3eb531ad7)

# museum:
![Screenshot 2025-04-14 152407](https://github.com/user-attachments/assets/79e8cb85-87f8-4940-a41d-24ae222127fe)

# RESULT
The program for implementing image maps using HTML is executed successfully.
