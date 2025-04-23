# Ex04 Places Around Me
## Date: 23.04.2025

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
            <font color="red"><b>PERAMBALUR</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>GOWTHAM S (212224100018)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#image-map">
            <map name="image-map">
                <area target="_blank" alt="Perambalur" title="Perambalur" href="perambalur.html" coords="1194,638,1376,707" shape="rect">
                <area target="_blank" alt="Campus" title="Campus" href="thanthai.html" coords="630,477,826,553" shape="rect">
                <area target="_blank" alt="Hospital" title="Hospital" href="hos.html" coords="1540,513,1738,600" shape="rect">
                <area target="_blank" alt="Aswin" title="Aswin" href="aswin.html" coords="1106,560,1329,614" shape="rect">
                <area target="_blank" alt="Subha" title="Subha" href="Hotel.html" coords="1335,771,1591,851" shape="rect">
            </map>
        </center>
    </body>
</html>
```

```
perambalur.html
<html>
    <head>
        <title>My Favourite Town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>perambalur</b></font>
        </h1>
        <h3 allign="center">
            <font color="blue"><b>PERAMBALUR-MY HOMETOWN</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="jusstify">
            <font face="Georgia" size="5">
                Perambalur is a landlocked district in central Tamil Nadu, approximately 267 km south of Chennai. Established in 1995, it covers an area of 1,757 square kilometers and has a population of around 565,000. The district is renowned for its agricultural productivity, notably producing about 24% of Tamil Nadu's small onions and being a significant producer of maize 
                Historically, it houses ancient Buddhist statues and the 15th-century Ranjankudi Fort, a prominent tourist attraction 
            </font>
        </p>
    </body>
</html>
```

```
thanthai.html
<html>
    <head>
        <title>My Favourite Town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>thanthai-school</b></font>
        </h1>
        <h3 allign="center">
            <font color="blue"><b></b></font>
        </h3>
        <hr size="3" color="red">
        <p align="jusstify">
            <font face="Georgia" size="5">
                Thanthai Roever Institute of Agriculture and Rural Development (TRIARD) is a prominent agricultural college located in Perambalur, Tamil Nadu.
                 Established in 1994 by the St. John Sangam Trust, it is affiliated with Tamil Nadu Agricultural University (TNAU) and approved by the Indian Council of Agricultural Research (ICAR) .
                 ​The curriculum encompasses various disciplines such as Agronomy, Soil Science, Agricultural Microbiology, Crop Physiology, Biochemistry, Agricultural Engineering,
                  Seed Science and Technology, Plant Breeding & Genetics, Biotechnology, Agricultural Entomology, Plant Pathology, Nematology, Vegetable Crops, Fruit Crops, Spices & Plantation Crops, Floriculture & Landscaping, 
                  and Medicinal Plants.
            </font>
        </p>
    </body>
</html>
```

```
Hotel.html
<html>
    <head>
        <title>My Favourite Town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>hotel-Subha residency</b></font>
        </h1>
        <h3 allign="center">
            <font color="blue"><b></b></font>
        </h3>
        <hr size="3" color="red">
        <p align="jusstify">
            <font face="Georgia" size="5">
                Hotel Subha Residency is a budget-friendly hotel located in Thuraimangalam, Perambalur, Tamil Nadu. Situated on SH 142,
                it's approximately 8.5 km from the city center and about 13.88 km from Sillakkudi railway station .​
                City Reviews

                🛏️ Accommodation & Amenities
                The hotel offers three types of rooms: Standard AC, Deluxe AC, and Suite. Amenities include air conditioning, free Wi-Fi, room service, 
                daily housekeeping, and 24/7 power backup. However, some guests have noted issues with cleanliness and maintenance, such as dirty bed sheets and non-functional bathroom fixtures .​

            </font>
        </p>
    </body>
</html>
```

```
hos.html
<html>
    <head>
        <title>My Favourite Town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Hopital-Priyam</b></font>
        </h1>
        <h3 allign="center">
            <font color="blue"><b></b></font>
        </h3>
        <hr size="3" color="red">
        <p align="jusstify">
            <font face="Georgia" size="5">
                Priyam Hospital, located in Perambalur, Tamil Nadu, was established on September 10, 2021, to address the growing healthcare needs in the region. Initially starting as a specialized bone and joint clinic, it has since expanded into a multispecialty facility offering 
                services in orthopedics, general surgery, plastic surgery, pediatrics, ENT, and psychiatry .​
                
                Key Features:
                Comprehensive Facilities: Priyam Hospital is equipped with modern amenities such as a 24/7 emergency and trauma service, 
                fully equipped operation theatres, an intensive care unit (ICU), laboratory services, ECG and X-ray facilities, and round-the-clock pharmacy services   
            </font>
        </p>
    </body>
</html>
```

```
aswin.html
<html>
    <head>
        <title>My Favourite Town</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Hotel-Aswins</b></font>
        </h1>
        <h3 allign="center">
            <font color="blue"><b></b></font>
        </h3>
        <hr size="3" color="red">
        <p align="jusstify">
            <font face="Georgia" size="5">
                Aswins Veg Restaurant is a well-known vegetarian dining establishment located in Perambalur, Tamil Nadu. Situated at No. 99A, North Side, Bhagavathi Complex, opposite the New Bus Stand Road in Thuraimangalam, the restaurant operates daily from 7:00 AM to 11:00 PM .​
                The restaurant offers a variety of South Indian and North Indian vegetarian dishes, including dosas, thalis, and sweets . It features both air-conditioned and non-air-conditioned dining areas, catering to different preferences . Customers have praised the food quality, especially the filter coffee 
                While many patrons appreciate the taste and ambiance, some reviews have highlighted areas for improvement, such as service efficiency and food consistency
            </font>
        </p>
    </body>
</html>
```

## OUTPUT

![image](https://github.com/user-attachments/assets/1ee3de6b-7d1a-4f46-84a4-2fd3b9f13d13)


![image](https://github.com/user-attachments/assets/9e05dd8c-cc4e-463e-8b75-6f1d37c4b571)

![image](https://github.com/user-attachments/assets/5690968f-ff7f-41b5-b9de-90a1c63d0d00)

![image](https://github.com/user-attachments/assets/0cc52f44-e639-4c84-a7fc-f4ece7fa774a)


![image](https://github.com/user-attachments/assets/75111d38-7235-42ec-9023-a19467fa4d2a)

![image](https://github.com/user-attachments/assets/3a65fe59-3763-47a0-951f-fb89fb857246)




## RESULT
The program for implementing image maps using HTML is executed successfully.
