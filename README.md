# Ex04 Places Around Me
## Date: 22/03/2024 

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
map.html
```
<html>
    <head>
        <title>thanjavur</title>
    </head>
    <body bgcolor="cyan">
        <h1> THANJAVUR CITY</h1>
        <h3>Name: S L Roop sagar</h3>
        <h3>Reg no:212223040175</h3>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="viyagula matha colony" title="viyagula matha colony" href="1.html" coords="1557,586,1342,535" shape="rect">
    <area target="" alt="melavelithottam" title="melavelithottam" href="2.html" coords="640,228,852,228,642,275,867,275,847,231,779,245,623,279" shape="poly">
    <area target="" alt="IFB point" title="IFB point" href="3.html" coords="734,570,891,604" shape="rect">
    <area target="" alt="periyakovil" title="periyakovil" href="4.html" coords="1337,310,1107,257" shape="rect">
    <area target="" alt="chellampatti" title="chellampatti" href="5.html" coords="1140,768,1308,809" shape="rect">
</map>
    </body>
</html>
```
1.html
```
<html>
<head>
    <title>viyagula matha colony</title>
</head>
<body bgcolor="blue">
    <h1>THANJAVUR CITY</h1>
    <h2>viyagula matha colony</h2>
    <hr>
    <p>Our Lady of Sorrows Church is located 
        at Vellicode in Kanyakumari District of
         Tamilnadu. This Church is also called as
          Vyakula Matha Church. Vellicode 
          (Sarva Valli Code as it was formerly known) 
          lies in the Kalkulam region of Nanjil Nadu.
           It is one of the oldest inhibited places in
            Nanjil Nadu.</p>
</body>
</html>
```
2.html
```
<html>
<head>
    <title>melavelithottam</title>
</head>
<body bgcolor="#43d4e6">
    <h1>THANJAVUR CITY</h1>
    <h2>melavelithottam</h2>
    <hr>
    <p>The Melavelithottam village is situated in the Thanjavur
         district with district code number 620. Thanjavur is the
          subdistrict (tehsil / mandal), is a low-level administrative
           division of a district, of this village, having the sub 
           district code is 05814. Thanjavur is the Community
            Development Block (C.D. Block) of this village with
             C.D. Block code number 0221. The gram panchayat for
              this village is Melaveli and its gram panchayat code 
              is 000026. Thanjavur is the Sub-district headquarter 
              of this village and it is situated 5 kilometres away 
              from this village. The district headquarters' name is 
              Thanjavur and as per distance concern it is 5 kilometres
               from the Melavelithottam village.

    </p>
</body>
</html>
```
3.html
```
<html>
<head>
    <title>IFB point</title>
</head>
<body bgcolor="#e5f240">
    <h1>THANJAVUR CITY</h1>
    <h2>IFB point</h2>
    <hr>
    <p>IFB Home Appliances is an Indian home appliances
         company and a division of IFB Industries. It has
          its manufacturing locations in Kolkata and Verna,
           Goa. The company has a chain of ~530 retail outlets
            called IFB Point. The IFB was part of this coalition,
             alongside the CBI, Institute for Business Ethics, TUC
              and others. In December 2018, the Wates Corporate
               Governance Principles were published, and companies 
               began reporting from their 2019 financial year.
    </p>
</body>
</html>
```
4.html
```
<html>
<head>
    <title>priyakovil</title>
</head>
<body bgcolor="#46ed9b">
    <h1>THANJAVUR CITY</h1>
    <h2>priyakovil</h2>
    <hr>
    <p>The original monuments of this 11th-century temple were
         built around a moat. It included gopura, the main temple,
          its massive tower, inscriptions, frescoes, and sculptures 
          predominantly related to Shaivism, but also of Vaishnavism 
          and Shaktism. The temple was damaged in its history and 
          some artwork is now missing. Additional mandapam and
           monuments were added in the centuries that followed.
            The temple now stands amidst fortified walls that were 
            added after the 16th century

    </p>
</body>
</html>
```
5.html
```
<html>
<head>
    <title>chellampatti</title>
</head>
<body bgcolor="#f048a7">
    <h1>THANJAVUR CITY</h1>
    <h2>chellampatti</h2>
    <hr>
    <p>Chellampatti is a small Village/hamlet in Orattanadu Block
         in Thanjavur District of Tamil Nadu State, India. It comes
          under Vadakkur South Panchayath. It is located 21 KM towards
           South from District head quarters Thanjavur. 10 KM from 
           Orattanadu. 343 KM from State capital Chennai.Chellampatti
            Pin code is 614902 and postal head office is Kottaitheru .
            Chellampatti is surrounded by Nanjikottai Block towards North ,
            Thanjavur Block towards North , Thiruvonam Block towards South ,
            Gandaravakottai Block towards west .
    </p>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-03-22 090551.png>) ![alt text](<Screenshot 2024-03-22 090629.png>) ![alt text](<Screenshot 2024-03-22 090750.png>) ![alt text](<Screenshot 2024-03-22 090813.png>) ![alt text](<Screenshot 2024-03-22 090926.png>) ![alt text](<Screenshot 2024-03-22 091259.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
