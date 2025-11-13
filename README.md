# Ex04 Places Around Me
## Date: 13/11/2025

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
<font color="red"><b>vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sharveshwaran M (212224240150)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,900,900" href="home.html" title="My Home Town">
<area shape="rect" coords="300,150,400,250" href="goldentemple.html" title="Golden Temple">
<area shape="rect" coords="600,300,700,400" href="jalakandeswarar.html" title="Jalakandeswarar Temple">
<area shape="rect" coords="850,100,950,200" href="palamathihills.html" title="Palamathi Hills">
<area shape="rect" coords="1100,250,1200,350" href="vellore.html" title="Vellore Fort">
<area shape="rect" coords="1250,400,1350,500" href="yelagirihills.html" title="Yelagiri Hills">
</map>
</center>
</body>
</html>

goldentemple.html

<html>
    <body>
        <center>
        <h1>Golden Temple</h1>
        <img src="c:\Users\admin\Downloads\WhatsApp Image 2025-11-10 at 19.02.00_84c3220a.jpg" height="300" width="500">
        </center>
        <font size="5">
            <li>Sri Lakshmi Narayani Golden Temple, located in Vellore, Tamil Nadu, spans 100 acres and is a spiritual park dedicated to Goddess Lakshmi.
                It features a unique star-shaped path extending 1.8 km, guiding devotees to the main shrine adorned with 1500 kg of pure gold foil. 
                The temple's architecture, embodying Vedic style, incorporates intricate gold craftsmanship and serene landscaped gardens. 
                Built in seven years by Sri Narayani Peedam under spiritual leader Sri Sakthi Amma, it attracts thousands for spiritual solace, meditation, and blessings. 
                The temple is renowned as the world's largest gold-coated temple and a symbol of divine prosperity and peace.</li>
        </font>
    </body>
</html>


jalakandeswarar.html

<html>
    <body>
        <center>
        <h1>Jalakandeswarar Temple</h1>
        <img src="c:\Users\admin\Downloads\WhatsApp Image 2025-11-10 at 19.02.01_f525a261.jpg" height="300" width="500">
        </center>
        <font size="5">
            <li>Jalakandeswarar Temple in Vellore, built in 1550 CE by Vijayanagara chieftain Chinna Bommi Nayaka, is a stunning example of Vijayanagara architecture. 
                The temple surrounds a Shiva Lingam originally hidden beneath an ant-hill in water, giving the deity the name Jalakandeswarar. 
                It features an impressive gopuram over 100 feet tall, intricately carved stone pillars, wooden gates, and monolith sculptures. 
                The temple is uniquely situated in the middle of a water tank and includes shrines to other deities and a notable wedding hall. 
                It is managed by the Archaeological Survey of India and remains a significant spiritual and historical landmark.</li>
        </font>
    </body>
</html>

palamathihills.html

<html>
    <body>
        <center>
        <h1>Palamathi Hills</h1>
        <img src="c:\Users\admin\Downloads\WhatsApp Image 2025-11-10 at 19.02.00_caae5c48.jpg" height="300" width="500">
        </center>
        <font size="5">
            <li>Palamathi Hills, an extension of the Eastern Ghats near Vellore, Tamil Nadu, is a scenic hill range known for its lush greenery, rich biodiversity, and serene environment. 
                It features the Otteri Lake, a man-made reservoir, and a temple dedicated to Lord Muruga atop the hill. 
                Popular for bird watching and trekking, it offers panoramic views of Vellore's countryside. 
                The area includes several small villages and supports agricultural activities, making it a peaceful natural retreat.</li>
        </font>
    </body>
</html>

vellore.html

<html>
    <body>
        <center>
        <h1>Vellore Fort</h1>
        <img src="c:\Users\admin\Downloads\WhatsApp Image 2025-11-10 at 19.02.00_9f242129.jpg" height="300" width="500">
        </center>
        <font size="5">
            <li>Vellore Fort, built in the 16th century by Vijayanagara chieftains, is a massive granite fortress in Tamil Nadu spreading over 133 acres. 
                Famous for its deep moat once home to 10,000 crocodiles, the fort features double walls, bastions, and robust military architecture. 
                It houses religious sites including Jalakandeswarar Temple, a mosque, and a church, plus museums and palaces. 
                The fort witnessed key historical events and ruled by Vijayanagara, Bijapur Sultanate, Marathas, and British, serving as a prison for notable figures like Tipu Sultan’s family. 
                It remains a prominent cultural and historical landmark.</li>
        </font>
    </body>
</html>


yelagirihills.html

<html>
    <body>
        <center>
        <h1>Yelagiri Hills</h1>
        <img src="c:\Users\admin\Downloads\WhatsApp Image 2025-11-10 at 19.02.02_25e5e725.jpg" height="300" width="500">
        </center>
        <font size="5">
            <li>Yelagiri Hills, located in Tamil Nadu's Vellore district, is a serene hill station at an altitude of 1,410 meters. 
                Known for its lush greenery, pleasant climate, and scenic beauty, it spans 30 square kilometers with 14 hamlets. 
                Popular attractions include the artificial Punganoor Lake, trekking paths, herbal farms, and temples. 
                Yelagiri hosts an annual summer festival and offers adventure activities like paragliding and rock climbing, attracting nature lovers and tourists alike.</li>
        </font>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (16).png>)
![alt text](<Screenshot (15).png>)
![alt text](<Screenshot (14).png>)
![alt text](<Screenshot (13).png>)
![alt text](<Screenshot (12).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
