# Ex03 Places Around Me
## Date:29.11.25

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE

```

map.html:
<html>
    <head>
        <title>My city map</title>
    </head>
    <body>
        <h1 style="text-align: center;">CHENGALPATTU</h1>
        <h4 style="text-align: center;">M.RITHIK(25014301)</h4>

        <img src="Screenshot 2025-11-26 113445.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Hotel Kanchi Boarding &amp; Lodging" title="Hotel Kanchi Boarding &amp; Lodging" href="hotel.html" coords="609,370,817,419" shape="rect">
    <area target="" alt="Gokulapuram" title="Gokulapuram" href="gokul.html" coords="463,349,85" shape="circle">
    <area target="" alt="Anna Nagar" title="Anna Nagar" href="anna.html" coords="619,596,740,650" shape="rect">
    <area target="" alt="Melamaiyur" title="Melamaiyur" href="mela.html" coords="872,553,965,573,963,642,821,644,801,563" shape="poly">
    <area target="" alt="Sivan Malai" title="Sivan Malai" href="temple.html" coords="1113,499,1277,543" shape="rect">
</map>
    </body>
</html>

temple.html:
<html>
    <head>
        <title>Sivan Malai</title>
    </head>
    <body bgcolor="beige">
        <h1 align="center">Sivan Malai</h1>
        <hr>
        <h2>The name "Sivan Malai" in Chengalpattu can refer to several temples, but most prominently to the ancient Vallam Hill Cave Temple, also known as the Pallavar Kugaivarai temple, a rock-cut cave temple built by the Pallava king Mahendra Varman approximately 1,300 years ago. Another possibility is the Pushpagiriswarar Temple in Pammal, which is also called Sivan Malai. There is also a Sivan Malai in Alapakkam, which is a separate Lord Shiva temple. </h2>
        <h1>Vallam Hill Cave Temple (Sivan Malai - Pallavar Kugaivarai Temple) </h1>
        <h2>Location: Vallam, Chengalpattu.</h2>
        <h2>History: Ancient cave temple believed to be 1,300 years old, built by Pallava king Mahendra Varman.</h2>
        <h1>Features:</h1>
        <h2>Sculptures and rock-cut architecture.</h2>
        <h2>Deities include Lord Ganesha, Lord Shiva, Balasubramaniyar, and Bhuvaneswari Amman.</h2>
        <h2>Serpentine arrangement for darshan: Ganesha, Shiva, and Amman.</h2>
        <h2>Visiting: Devotees can contact the priest, Mr. Chellappa Gurukkal, via the number displayed at the temple for poojas. </h2>
    </body>
</html>

mela.html:
<html>
    <head>
        <title>Melamaiyur</title>
    </head>
    <body bgcolor="salmon">
        <h1 align="center">Melamaiyur</h1>
        <hr>
        <h2>Melamaiyur is a village and a locality in the Chengalpattu district of Tamil Nadu, known for its residential areas and growing infrastructure. It has a total population of 8,468 as per 2011 census data, with a high literacy rate and a young demographic. The area offers both public and private transportation options, with the nearest railway station located close to the town, making it a convenient place for residents. </h2>
        <h1>Demographics and governance</h1>
        <h2>Population: 8,468 (as of 2011 Census), with slightly more females than males.</h2>
        <h2>Children (0-6 years): 928, making up 11% of the total population.</h2>
        <h2>Literacy Rate: 92.9% (as of 2011), with male literacy at 95.85% and female literacy at 90.11%.</h2>
        <h2>Administration: The village is administered by an elected Sarpanch (Head of Village).</h2>
        <h2>Households: 2,153 families reside in the village (as of 2011). </h2>
    </body>
</html>

Anna.html:

<html>
    <head>
        <title>Anna Nagar</title>
        <body bgcolor="wheat">
            <h1 align="center">Anna Nagar</h1>
            <hr>
            <h2>Anna Nagar is an emerging residential locality in the Chengalpattu district, known for being a fast-developing suburb on the outskirts of Chennai. It offers a blend of peaceful, green surroundings with urban convenience due to its strategic location near major highways and industrial hubs. The area has well-planned layouts, good connectivity via roads like the GST Road (NH-32) and upcoming Chennai Peripheral Ring Road, and growing investment potential. </h2>
            <h1>Key features</h1>
            <h3>Location: A growing residential area in the Chengalpattu district, with specific locations including Mevaloorkuppam, Kolapakkam, and Irunkattukottai.</h3>
            <h3>Environment: Characterized by lush greenery, serene surroundings, and well-planned layouts, providing a tranquil lifestyle away from the city center.</h3>
            <h3>Connectivity: Well-connected via major arterial roads such as the Grand Southern Trunk (GST) Road (NH-32) and the Chennai-Bengaluru Highway (NH 48). It also has access to Chengalpattu's bus stand and railway station. The upcoming Chennai Peripheral Ring Road is expected to further improve connectivity.</h3>
            <h3>Proximity to hubs: Strategically located near key industrial corridors and IT hubs, making it an attractive option for professionals and families working in the Sriperumbudur and Maraimalai Nagar areas.</h3>
            <h3>Development: A rapidly developing area with a mix of independent houses and modern apartment complexes. It has a growing population of working professionals and families.</h3>
            <h3>Investment Potential: Considered a promising investment destination due to its increasing property values, affordability, and strong potential for capital appreciation. Its proximity to industrial zones also ensures steady rental demand. </h3>
        </body>
    </head>
</html>

gokul.html:
<html>
    <head>
        <title>Gokulapuram</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">Gokulapuram</h1>
        <hr>
        <h2>Gokulapuram is a residential area in Chengalpattu, Tamil Nadu, known for being a peaceful and developing locality with good connectivity to major hubs. It offers a blend of urban convenience and a serene environment, with a mix of independent houses and apartments. The area is strategically located near the Chengalpattu railway station, the Chennai-Bengaluru Highway, and is close to industrial and IT hubs like Mahindra World City, making it attractive for both residents and investors. </h2>
        <h2>Location and connectivity</h2>
        <h3>Strategic location: Situated within Chengalpattu town, it is close to the Chennai-Bengaluru Highway (NH 48) and the Chengalpattu railway station.</h3>
        <h3>Proximity to hubs: It is well-connected to major industrial and IT centers like Mahindra World City, Maraimalai Nagar, and Singaperumal Koil.</h3>
        <h3>Administrative significance: It falls under the jurisdiction of the Chengalpattu Sub-Registrar Office and is near the District Registrar Office and DIG office. </h3>
    </body>
</html>

hotel.html:

<html>
    <head>
        <title>Kanchi Hotel</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">Kanchi Hotel</h1>
        <hr>
        <h2>Since 2004, KAYAK has been revolutionising the travel industry. Metasearch for travel? No one was doing it. Until we did.</h2>
        <h3>KAYAK was created for travellers, by travellers, born from a simple belief: travel makes the world better.

The more people we can help experience the world, the better it becomes for everyone. So we built something that makes getting there easier. We pioneered the concept of travel metasearch with every traveller in mind. Because no matter your budget, preferences or favourite providers, you should be able to compare all your options in one place.

We built the site we wanted to use: an experience that puts control back in travellers’ hands. No more searching hundreds of sites on your own - just a smarter, faster way to see all of your choices and plan trips with confidence.

Today, we’re proud to be the world’s leading travel search engine, processing billions of searches, partnering with hundreds of global travel brands and earning the trust of millions of leisure and business travellers worldwide. Yet, our core values remain exactly as they were on day one.</h3>
<h2>What we believe.</h2>
<h3>Transparency and choice belong to every traveller.
Our platform makes it easy to compare options, understand total costs and book with confidence.- No hidden fees. No surprises.

The magic happens when you can see all of your options.
KAYAK was designed to be comprehensive, surfacing offers directly from airlines and trusted third-party sources so travellers can see the full picture before booking.

We don’t play favourites.
We partner with hundreds of travel providers to display fares, schedules and amenities accurately and fairly. Our results are based on what’s best for the traveller - not on whom we partner with.

A transparent marketplace benefits everyone.
An open travel marketplace where travellers gain real choice is good for travellers and partners. By maintaining equal access to public fares and clearly labelling booking sources (“Book with Airline” or “Book with Partner”), we protect consumer trust and promote healthy, competitive distribution across the travel ecosystem.</h3>
    </body>
</html>

```

## OUTPUT

map.html:
![alt text](<Screenshot 2025-11-29 082550.png>)

mela.html:
![alt text](<Screenshot 2025-11-29 082603.png>)

gokul.html:
![alt text](<Screenshot 2025-11-29 082616.png>)

hotel.html:
![alt text](<Screenshot 2025-11-29 082631.png>)

temple.html:
![alt text](<Screenshot 2025-11-29 082646.png>)

anna.html:
![alt text](<Screenshot 2025-11-29 082700.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
