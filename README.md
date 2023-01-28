# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository into Theia IDE

### Step 2:
Create a new Django project

### Step 3:
Write the needed HTML code

### Step 4:
Run the Django server and execute the HTML files

## Code:
map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="green"><b>CHENNAI - GUINDY</b></font>
</h1>
<h3 align="center">
<font color="black"><b>DINESHSEKHAR (22008100)</b></font>
</h3>
<center>
<img src="/static/images/mapp.png" usemap="#MyCity" height="600" width="1200">
<map name="MyCity">
<area shape="rectangle" coords="99,275,447,451" href="/static/html/guindy.html" title="Guindy National Park">

<area shape="circle" coords="185,89,80" href="/static/html/mandapam.html" title="Gandhi Mandapam">
<area shape="poly" coords="881,83,943,288,1098,90" href="/static/html/iit.html" title="IIT MADRAS">
<area shape="rectangle" coords="436,49,522,122" href="/static/html/rajaji.html" title="Rajaji Memorial">
<area shape="circle"coords="328,171,65"href="/static/html/mandapam.html"title="Gandhi Museum">
</map>
</center>
</body>
</html>
```
rajaji.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <title>RAJAJI MEMORIAL</title>
</head>

<body bgcolor="cyan">
    <h1 align="center">
        <font color="white"><b>CHEENAI - GUINDY</b></font>
    </h1>
    <h3 align="center">
        <font color="white"><b>RAJAJI MEMORIAL</b></font>
    </h3>
    <hr size="3" color="black">
    <p align="justify">
        <font face="Tahoma" size="5">
            <b>
               Rajaji Memorial in Thorapalli is the house that Chakravarthi Rajagopalachari (10 December 1878–25 December 1972) was born and raised in till he was 11 years old.
               C. Rajagopalachari, or Rajaji as he is fondly remembered, was a freedom fighter and a leader of caliber. 
               C. Rajagopalachari was not only the chief minister of Tamil Nadu, he was the leader of the Indian National Congress,


            </b>
        </font>
    </p>
</body>
</html>
```
guindy.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>GUINDY NATIONAL PARK</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="white"><b>CHENNAI - GUINDY</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>GUINDY NATIONAL PARK</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
Guindy National Park is a 2.70 km2 (1.04 sq mi) protected area of Tamil Nadu, located in Chennai, India, 
is the 8th-smallest National Park of India and one of the very few national parks situated inside a city.
</font>
</p>
</body>
</html>
```
iit.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>IIT MADRAS</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>CHENNAI - GUINDY</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>IIT MADRAS</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
IIT Madras is a residential institute with nearly 550 faculty, 8000 students and 1250 administrative & supporting staff and is a self-contained campus located in a beautiful wooded land of about 250 hectares. 
The campus is located in the city of Chennai, previously known as Madras.
</b>
</font>
</p>
</body>
</html>
```
mandapam.html
```
<!DOCTYPE html>
<html lang="en">

<head>
<title>Gandhi Mandapam</title>
</head>

<body bgcolor="brown">
<h1 align="center">
<font color="white"><b>CHENNAI - GUINDY</b></font>
</h1>
<h3 align="center">    <font color="white"><b>Gandhi Mandapam</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Tahoma" size="5">
<b>
 Gandhi Mandapam is a series of memorial structures built on Sardar Patel Road, in Adyar, Chennai.
 The first structure to be built on the premises was a memorial to Mahatma Gandhi, opened by then Chief Minister of Madras, C. Rajagopalachari on 27 January 1956. Later, four other memorials for independence activist Rettamalai Srinivasan and former chief ministers C. Rajagopalachari, K. Kamaraj and M. Bhakthavatsalam were added.
 Owing to its prominence, the premise is often utilized for public functions, particularly for cultural discourses and music shows.
 The site also serves as a recreational park in the city.
It is located nearby Anna University and IIT Madras.
</b>    </font>
</p>
</body>
</html>
```

## Output:
Map
![map](https://user-images.githubusercontent.com/119405916/215278099-0d692916-a294-45ec-b5dc-108d0eb5a08b.png)

Guindy
![guindy](https://user-images.githubusercontent.com/119405916/215278121-d46a8ab2-c91c-46ae-87a5-1814aac3ca82.png)

IIT
![iit](https://user-images.githubusercontent.com/119405916/215278135-93892504-7a7b-4f50-ad6d-f7a95820f390.png)

Rajaji
![rajaji](https://user-images.githubusercontent.com/119405916/215278161-f9a03a8f-a16d-4eb4-b081-2dc1ba1c3551.png)

Mandapam
![mandapam](https://user-images.githubusercontent.com/119405916/215278181-2c383e53-ca9d-4c3c-bd7c-60267df71d2d.png)


## HTML Validator:
![html](https://user-images.githubusercontent.com/119405916/215278208-2dc332a1-4e8b-4d4a-ae4c-c77ced38d83c.png)


## Result:
The program for implementing image map is executed successfully.
