# Ex04 Places Around Me

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
## map.html
```

<html>
    <head>
        <title>Villupuram</title>
        <style>
            h1{
                font-family: Algerian;
                color: rgb(236, 11, 79);
                font-size: large;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Villupuram  </h1>
        <center>
            <img src="villupuram.png" usemap="#mapnew" lenght="1000" width="1000">
            
            <map name="mapnew">
                <area target="" alt="Auroville" title="Auroville" href="Auroville.html" coords="296,253,596,337" shape="rect">
                <area target="" alt="Gingee" title="Ginjee Fort" href="Gingee.html" coords="310,210,50" shape="circle">
                <area target="" alt="Veedur" title="Veedur Dam" href="Veedur.html" coords="520,487,667,569" shape="rect">
                <area target="" alt="" title="Sri Manakula vinayagar temple" href="vinayagar.html" coords="355,417,39" shape="circle">
                </map> 
        </center> 
    </body>
</html>
```
## Auroville.html
```
<html>
    <head>
        <title>Auroville</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">Auroville near Pondicherry</h1>
        <p>Auroville (/ˈɔːrəvɪl/; City of Dawn French: Cité de l'aube) is an experimental township in Viluppuram district, mostly in the state of Tamil Nadu, India, with some parts in the Union Territory of Pondicherry in India.[3] It was founded in 1968 by Mirra Alfassa (known as "the Mother") and designed by architect Roger Anger.[4][5][6] At its Annual Conference in 1964 and with Mirra Alfassa as its Executive President, the Sri Aurobindo Society in Pondicherry passed a resolution for the establishment of a city dedicated to the vision of Sri Aurobindo. Alfassa was the spiritual collaborator of Sri Aurobindo, who believed that "man is a transitional being." Alfassa expected that this experimental "universal township" would contribute significantly to the "progress of humanity towards its splendid future by bringing together people of goodwill and aspiration for a better world". Alfassa also believed that such a universal township would contribute decisively to the Indian Renaissance.[8]</p>
        
            <img align="left" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/The_Matrimandir_in_Auroville%2C_Tamil_Nadu%2C_India.jpg/330px-The_Matrimandir_in_Auroville%2C_Tamil_Nadu%2C_India.jpg" height="450" width="500">
            <img align="right" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Town_Hall_of_Auroville.jpg/375px-Town_Hall_of_Auroville.jpg" height="450" width="450">
            <img align="right" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/Courtyard_of_the_Tibetan_Centre%2C_Auroville_01.jpg/330px-Courtyard_of_the_Tibetan_Centre%2C_Auroville_01.jpg" height="450" width="450">
</html>
```
## Ginjee.html
```
<html>
    <head>
        <title>Genjee Fort</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">Genjee Fort</h1>
        <p>Gingee Fort or Senji Fort (also known as Chenji, Chanchi, Jinji or Senchi) in Tamil Nadu, India is one of the surviving forts in Tamil Nadu, India. It lies in Villupuram District, 160 kilometres (99 mi) from the state capital, Chennai, and is close to the Union Territory of Puducherry. The site is so fortified that Chhatrapati Shivaji Maharaj, the Maratha king, ranked it as the "most impregnable fortress in India", and it was called the "Troy of the East" by the British. The nearest town with a railway station is Tindivanam and the nearest airport is Chennai (Madras), located 150 kilometres (93 mi) away.</p>
            <img align="left" src="https://encrypted-tbn2.gstatic.com/licensed-image?q=tbn:ANd9GcS2-mOVGkvtUt6y2nnFyFS8LGQ0YBhOk33VsBNkdaWF9koEJRiGIdLj9K_1O1_cFcuyxVRKBfDkQivAvajvmH0cf2cRvplNxMPoxDT_0g" height="450" width="500">
            <img align="right" src="https://encrypted-tbn1.gstatic.com/licensed-image?q=tbn:ANd9GcRYRGLsd1xwGlxHSiF4bnZMMPqLfpm2bSNfjzrbB_vprt8dXmiiHFLBmi6eXsDm_R9_ofaxjDtrwm6TAFfWSbAK_DtPbGLTqnvUM5IXsQ" height="450" width="450">
            <img align="center" src="https://encrypted-tbn0.gstatic.com/licensed-image?q=tbn:ANd9GcR3GsF7S49Z0JgjhFszl4rm9xG1qwq3yePtK-kRlWLY5emHJV1raVL40TatxV1KCoi6AzjHfWwXKXXZukDm1Il2sqxiiHM5VV30ad5Ol4w" height="450" width="500">
     </body>
</html>
```
## Veedur.html
```
<html>
    <head>
        <title>Veedur Dam</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">Veedur dam</h1>
        <p>Veedur is a village panchayat in the Viluppuram district of Tamil Nadu state, India. It is the largest village by area and population in the district. National Highway No. 45, from Chennai to Dindigul via Tiruchirapalli, goes through the hamlet.Veedur lies in the northeast part of Tamil Nadu, between Chennai and Villupuram. It is 142 km (101 mi) south of Chennai and 50 km (98 mi) north of Pondicherry</p>
            <img align="left" src="https://lh5.googleusercontent.com/p/AF1QipOEGOnV16B6z70e3QvcLX79OVPFMR-E5ETlmR-H=w675-h390-n-k-no" height="450" width="500">
            <img align="right" src="https://lh5.googleusercontent.com/p/AF1QipMh-8OIMD3JGyl0e7FPGf7XlQihcLpnusGdsJ1i=w675-h390-n-k-no" height="450" width="450">
            <img align="right" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjI1NfmF2egbeGQdGvyQ7ndbcvEQ-aYMrCJA5VDyFMjC9UY_tbn6K3s0yZqUtf9Y1ToqwRcuiS8b1QaRNA1oCDxly_f1cNvRWOWRkXm_QdnTrKtn4muu14I4_2PZnOw8LxYBVOwDw/w640-h480/IMG_3483.jpg" height="450" width="450">
</html>
```
## Vinayagar.html
```
<html>
    <head>
        <title>Sri Manakula Vinayagar temple</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">Sri Manakula Vinayagar temple</h1>
        <p>Manakula Vinayagar Temple is a Ganesha temple in the Union Territory of Puducherry, India. Dedicated to the god Ganesa, it is a popular pilgrimage site and tourist destination in Puducherry.[1] The temple is of considerable antiquity and predates French occupation of the territory. During the tenure of Dupleix, there were attempts to destroy the temple, but it was spared owing to strong protests from the Hindu population and the threat of British and Maratha invasion of the territory.</p>
            <img align="left" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Manakula_vinayagar_temple_north_entrance.JPG/330px-Manakula_vinayagar_temple_north_entrance.JPG" height="450" width="500">
            <img align="right" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Manakula_Vinayagar_Temple._Near_Pondicherry%2C_2010.jpg/450px-Manakula_Vinayagar_Temple._Near_Pondicherry%2C_2010.jpg" height="450" width="450">
</html>
```
## OUTPUT
## Map
![Screenshot 2024-10-14 145828](https://github.com/user-attachments/assets/09a6b19b-8df0-400c-a596-51d48cfa4296)

## Auroville
![Screenshot 2024-10-14 150046](https://github.com/user-attachments/assets/ca7a840e-7f86-4706-bce5-6087a804a7ed)
## Genjee Fort
![Screenshot 2024-10-14 150059](https://github.com/user-attachments/assets/8c872e3c-cb36-4a59-a580-37a7ab00d45b)
## Veedur
![Screenshot 2024-10-14 150110](https://github.com/user-attachments/assets/8ba3fd4d-3872-4f45-a2fc-6ed4bba34b68)
## Vinayager
![Screenshot 2024-10-14 150121](https://github.com/user-attachments/assets/9e35b677-dc42-4e47-b483-fdead00b9d93)












## RESULT
The program for implementing image maps using HTML is executed successfully.
