# Ex04 Places Around Me
# Date:5/10/24
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="container">
        <div class="container">
        <!-- Image Map Generated by http://www.image-map.net/ -->
<img src="map.jpg" usemap="#image-map">

<map name="image-map">
    <area target="" alt="manavalanallur" title="manavalanallur" href="file:///C:/Users/admin/Desktop/imap/manavalanallur.html" coords="45,396,218,394,211,465,46,473" shape="poly">
    <area target="" alt="sathukudal" title="sathukudal" href="file:///C:/Users/admin/Desktop/imap/sathukudal.html" coords="407,462,512,463,512,520,400,526" shape="poly">
    <area target="" alt="virudhachalam" title="virudhachalam" href="file:///C:/Users/admin/Desktop/imap/virudhachalam.html" coords="539,311,741,300,739,372,552,380" shape="poly">
    <area target="" alt="ponneri" title="ponneri" href="file:///C:/Users/admin/Desktop/imap/ponneri.html" coords="859,256,960,250,952,310,866,317" shape="poly">
    <area target="" alt="karkudal" title="karkudal" href="file:///C:/Users/admin/Desktop/imap/karkudal.html" coords="832,625,939,623,947,678,843,680" shape="poly">
</map>
        </div> 
    </div>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
    
    <style>

body, html {
    margin: 0;
    padding: 0;
    height: 100%;
}


body {
    background:url(virudhachalam.jpg);
    background-size: cover; 
    background-repeat: no-repeat; 
    background-position: center; 
    font-family: Arial, sans-serif; 
    color: white; 
    text-align: center; 
}


header {
    margin-top: 20%;
    background-color: rgba(0, 0, 0, 0.5); 
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
}

        </style>
</head>
<body>
    <header>
        <h1>(VIRUDHACHALAM)</h1>
        <p>Location: Virudhachalam is a municipality and taluk headquarters in the Cuddalore district of Tamil Nadu. 
            Population: As of 2011, the population of Virudhachalam was 73,585. 
            Ancient name: The ancient name of Virudhachalam was Thirumudhukundram<p>
    </header>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
    
    <style>

body, html {
    margin: 0;
    padding: 0;
    height: 100%;
}


body {
    background: linear-gradient(rgba(24, 26, 24, 0.605),rgba(30, 33, 30, 0.7)),url(oooo\ \(1\).jpg);
    
    background-size: cover; 
    background-repeat: no-repeat; 
    background-position: center; 
    font-family: Arial, sans-serif; 
    color: white; 
    text-align: center; 
}


header {
    margin-top: 20%;
    background-color: rgba(0, 0, 0, 0.5); 
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
}

        </style>
</head>
<body>
    <header>
        <h1>(SATHUKUDAL)</h1>
        <p>Sathukudal is a village situated in Virudhachalam taluka of Cuddalore district in Tamil Nadu. As per the Population Census 2011, there are a total of 418 families residing in the village Sathukudal.<p>
    </header>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
    
    <style>

body, html {
    margin: 0;
    padding: 0;
    height: 100%;
}


body {
    background: linear-gradient(rgba(24, 26, 24, 0.605),rgba(30, 33, 30, 0.7)),url(ooo\ \(1\).jpg);
    
    background-size: cover; 
    background-repeat: no-repeat; 
    background-position: center; 
    font-family: Arial, sans-serif; 
    color: white; 
    text-align: center; 
}


header {
    margin-top: 20%;
    background-color: rgba(0, 0, 0, 0.5); 
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
}

        </style>
</head>
<body>
    <header>
        <h1>(PONNERI)</h1>
        <p>Gram Panchayat :	Ko Mavidnathal
            Block / Taluka :	Virudhachalam
            District :	Cuddalore
            State :	Tamil Nadu
            Pincode :	606003
            Area :	195.52 hectares<p>
    </header>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
    
    <style>

body, html {
    margin: 0;
    padding: 0;
    height: 100%;
}


body {
    background: linear-gradient(rgba(24, 26, 24, 0.605),rgba(30, 33, 30, 0.7)),url(ooooo\ \(1\).jpg);
    
    background-size: cover; 
    background-repeat: no-repeat; 
    background-position: center; 
    font-family: Arial, sans-serif; 
    color: white; 
    text-align: center; 
}


header {
    margin-top: 20%;
    background-color: rgba(0, 0, 0, 0.5); 
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
}

        </style>
</head>
<body>
    <header>
        <h1>(MANAVALANALLUR])</h1>
        <p>Locality Name : Manavalanallur ( மணவாளநல்லூர் )
            Block Name : Vriddhachalam
            District : Cuddalore
            State : Tamil Nadu
            Language : Tamil And English
            Current Time 08:44 PM
            Date: Saturday , Nov 30,2024 (IST)
            Time zone: IST (UTC+5:30)
            Elevation / Altitude: 45 meters. Above Seal level
            Telephone Code / Std Code: 04149<p>
    </header>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
    
    <style>

body, html {
    margin: 0;
    padding: 0;
    height: 100%;
}


body {
    background: linear-gradient(rgba(24, 26, 24, 0.605),rgba(30, 33, 30, 0.7)),url(karkudal.jpg);
    
    background-size: cover; 
    background-repeat: no-repeat; 
    background-position: center; 
    font-family: Arial, sans-serif; 
    color: white; 
    text-align: center; 
}


header {
    margin-top: 20%;
    background-color: rgba(0, 0, 0, 0.5); 
    padding: 20px;
    border-radius: 10px;
    display: inline-block;
}

        </style>
</head>
<body>
    <header>
        <h1>(KARKUDAL)</h1>
        <p>Karkudal is located in the Kammampuram taluk of the Cuddalore district.
            It is part of the Puvanagiri legislative assembly constituency and the Chidambaram parliamentary constituency<p>
    </header>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2024-12-13 104216.png>)
![alt text](<Screenshot 2024-12-13 104102.png>)
![alt text](<Screenshot 2024-12-13 104049.png>)
![alt text](<Screenshot 2024-12-13 103951.png>)
![alt text](<Screenshot 2024-12-13 103936.png>)
![alt text](<Screenshot 2024-12-13 103918.png>)
# RESULT
The program for implementing image maps using HTML is executed successfully.
