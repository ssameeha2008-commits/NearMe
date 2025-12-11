# Ex04 Places Around Me
## Date:11.12.2025

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
MAP.HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Image Map Example</title>
</head>
<body>

<h2>Clickable Map Locations</h2>


<img src="map.png" alt="Chennai Map" usemap="#mymap" width="1520">


<map name="mymap">
  
  <area shape="circle" coords="90,286,101" href="Kolathur.html" alt="Kolathur" target="_blank">
  <area shape="circle" coords="491,301,98" href="Perambur.html" alt="Perambur" target="_blank">
  <area shape="rect" coords="300,702,832,812" href="Ayanavaram.html" alt="Ayanavaram" target="_blank">
  <area shape="rect" coords="356,443,594,528" href="Spectrum The Grand Venus Mall.html" alt="Spectrum The Grand Venus Mall" target="_blank">
  <area shape="rect" coords="156,-2,372,76" href="Meridian Hospital.html"  alt="Meridian Hospital" target="_blank">
</map>

</body>
</html>

KOLATHUR.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Famous Kolathur, Chennai</title>
</head>
<body  bgcolor="plum">

    <h1>Kolathur, Chennai: What It Is Famous For</h1>

    <p>Kolathur is a well-known residential area in North Chennai.</p>

    <h2>The Main Attraction:</h2>

    <p>The locality is most famous for its <b>Ornamental Fish Market</b>.</p>
    
    <h3>Key features of the market:</h3>
    <ul>
        <li>It is one of the largest centers for <strong>aquarium fish trade</strong> in the city.</li>
        <li>A wide variety of <strong>colorful tropical fish</strong> and aquatic supplies are sold here.</li>
        <li>It is a hub for fish hobbyists and dealers across Tamil Nadu.</li>
    </ul>

    <h2>Other Important Aspects:</h2>
    <p>Kolathur is also significant as:</p>
    <ol>
        <li>A well-developed <b>residential area</b> with good connectivity.</li>
        <li>It is located close to the <strong>Jawaharlal Nehru Road</strong> (Inner Ring Road).</li>
        <li>It is home to several <b>ancient temples</b>.</li>
    </ol>

    <hr>
    <p><em>Note: This information provides a simple overview of the area's fame.</em></p>

</body>
</html>

PERAMBUR.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Famous Perambur, Chennai</title>
</head>
<body bgcolor="lightcoral">

    <h1>Perambur, Chennai: What It Is Famous For</h1>

    <p>Perambur is one of the oldest and most prominent residential neighbourhoods in North Chennai.</p>

    <h2>The Main Attraction:</h2>

    <p>Perambur's fame is largely due to the <b>Integral Coach Factory (ICF)</b>.</p>

    <h3>About the Integral Coach Factory:</h3>
    <ul>
        <li>The ICF is a premier manufacturing unit of the <strong>Indian Railways</strong>.</li>
        <li>It is one of the largest coach manufacturers in the world.</li>
        <li>It produces various types of rolling stock for both Indian and international railways.</li>
    </ul>

    <h2>Other Key Aspects:</h2>
    <p>The area is also known for:</p>
    <ol>
        <li>Its large and well-established <b>residential colonies</b>, particularly those associated with the ICF.</li>
        <li>The presence of the <b>Spectrum The Grand Venus Mall</b>, one of the major shopping centers in North Chennai.</li>
        <li>Its excellent <b>rail connectivity</b>, including the Perambur railway station.</li>
    </ol>

    <hr>
    <p><i>Perambur is a historic hub of industrial and residential life in the city.</i></p>

</body>
</html>

AYYANAVARAM.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Famous Ayyanavaram, Chennai</title>
</head>
<body bgcolor="sandybrown">

    <h1>Ayyanavaram, Chennai: What It Is Famous For</h1>

    <p>Ayyanavaram is a well-established and centrally located residential neighborhood in Chennai.</p>

    <h2>The Main Connection:</h2>

    <p>The locality is strongly connected to the <b>Indian Railways infrastructure</b>.</p>

    <h3>Key Railway Links:</h3>
    <ul>
        <li>It is located close to the <strong>Perambur Carriage Works</strong> railway facilities.</li>
        <li>It serves as an important junction and residential area for railway employees.</li>
    </ul>

    <h2>Other Important Aspects:</h2>
    <p>Ayyanavaram is also significant for:</p>
    <ol>
        <li>Its large and old <b>residential base</b>.</li>
        <li>Having a major <b>police station</b> that covers a large part of Central Chennai.</li>
        <li>Its good location, providing easy access to areas like Kilpauk and Anna Nagar.</li>
    </ol>

    <hr>
    <p><i>Ayyanavaram combines residential convenience with a strong historical link to the city's railway system.</i></p>

</body>
</html>

SPECTRUM MALL.HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Famous Spectrum Mall, Chennai</title>
</head>
<body bgcolor="skyblue">

    <h1>Spectrum The Grand Venus Mall: What It Is Famous For</h1>

    <p>Spectrum Mall is a prominent shopping and entertainment center located in Perambur, North Chennai.</p>

    <h2>The Main Attraction:</h2>

    <p>It is famously recognized as the <b>First Major Mall in North Chennai</b>.</p>

    <h3>Key Features of the Mall:</h3>
    <ul>
        <li>It is a popular destination for <strong>retail shopping</strong> and family entertainment.</li>
        <li>It houses a modern <strong>multiplex cinema (S2/PVR Cinemas)</strong>, making it a major movie destination.</li>
        <li>It offers a spacious <strong>Food Court</strong> with multiple restaurant options.</li>
        <li>The mall is known for bringing a modern shopping experience to the North Chennai region.</li>
    </ul>

    <h2>Location and History:</h2>
    <p>The mall is situated on Paper Mills Road and was built on the site of the erstwhile <b>Venus Theatre</b>.</p>

    <hr>
    <p><i>Spectrum Mall serves as a central hub for shopping, food, and movies in Perambur.</i></p>

</body>
</html>

MERDIAN HOSPITAL .HTML


<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Famous Meridian Hospital, Chennai</title>
</head>
<body bgcolor="peachpuff">

    <h1>Meridian Hospital: What It Is Famous For</h1>

    <p>Meridian Hospital is a recognized healthcare institution located in the Kolathur area of Chennai.</p>

    <h2>The Main Reputation:</h2>

    <p>The hospital is primarily known as a <b>Multi-Specialty Hospital</b> providing comprehensive medical services to the surrounding neighborhoods.</p>

    <h3>Key Features and Services:</h3>
    <ul>
        <li>It provides a wide range of medical services across various <strong>specialties</strong>.</li>
        <li>It is a key medical facility serving the residents of <strong>Kolathur</strong> and North Chennai.</li>
        <li>It is known for its <strong>24/7 Emergency and Trauma Care</strong> services.</li>
    </ul>

    <h2>Location and Accessibility:</h2>
    <p>The hospital is conveniently located on the <b>Jawaharlal Nehru Road (200 Feet Ring Road)</b>, ensuring good accessibility.</p>

    <hr>
    <p><i>Meridian Hospital is a vital part of the healthcare infrastructure in North Chennai.</i></p>

</body>
</html>


## OUTPUT


<img width="1919" height="814" alt="image" src="https://github.com/user-attachments/assets/19247e3a-21fc-4d93-92fd-a4bfe89a2aa7" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3b0203a0-6c2d-4661-9a55-f4139d3ca5e6" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fe0e1b04-88b8-47c6-bb03-74788e39a6fd" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ce04b6ce-dd86-478f-95e8-d196e6a5bed1" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/31d1d58b-ee32-4c18-be2c-37f7e5d5f0fa" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9e683814-dfc5-4a84-8b8a-8f5ea05e7459" />

## RESULT
The program for implementing image maps using HTML is executed successfully.
