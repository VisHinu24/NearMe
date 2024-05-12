# Ex04 Places Around Me
## Date: 18/03/2024
## Name : H Vishinu 
## Reg.No : 212223220124
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
Main
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MAP</title>
</head>
<center>
<body bgcolor="grey">
    <h1>Image Mapping</h1>
    <h2>VisHinu H(212223220124)</h2>
    <img src="map.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="M M Hospital" title="M M Hospital" href="hos.html" coords="154,512,55" shape="circle">
        <area target="" alt="PSM sports vilage" title="PSM sports vilage" href="vil.html" coords="798,377,43" shape="circle">
        <area target="" alt="Chennai Intercity football academy" title="Chennai Intercity football academy" href="football.html" coords="549,393,54" shape="circle">
        <area target="" alt="Puzhal Lake" title="Puzhal Lake" href="lake.html" coords="1212,651,296" shape="circle">
        <area target="" alt="Dog House" title="Dog House" href="dog.html" coords="997,150,71" shape="circle">
    </map>
</body>
</center>
</html>
```
Village 
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>PSM Sports Village</title>
<link rel="stylesheet" href="des.css">
</head>
<body>
<div id="header">
  <h1>PSM Sports Village</h1>
</div>
<div id="content">
  <h2>About PSM Sports Village</h2>
  <p>PSM Sports Village is your ultimate destination for sports, fitness, and recreation in Chennai.</p>
  <h3>Facilities</h3>
  <ul>
    <li>State-of-the-Art Sports Complex</li>
    <li>Fitness Center</li>
    <li>Swimming Pool</li>
    <li>Multipurpose Courts</li>
    <li>Children's Play Area</li>
  </ul>
  <h3>Events and Programs</h3>
  <p>Stay tuned for exciting events, tournaments, and programs hosted regularly at PSM Sports Village.</p>
  <h3>Membership</h3>
  <p>Unlock unlimited access to all amenities with our flexible membership options.</p>
</div>
</body>
</html>

```
Dog House
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Dog Houses</title>
<link rel="stylesheet" href="des.css">
</style>
</head>
<body>
<div id="header">
  <h1>Dog Houses</h1>
</div>
<div id="content">
  <h2>Providing Comfort and Shelter for Your Canine Companion</h2>
  <p>Dog houses are essential for providing your furry friend with a safe and comfortable outdoor shelter. Whether your dog spends most of their time outdoors or just needs a cozy spot to retreat to, a well-designed dog house is a must-have.</p>
  <h3>Key Features of a Quality Dog House</h3>
  <ul>
    <li><strong>Insulation:</strong> Ensure that the dog house provides adequate insulation to keep your dog warm in colder months and cool in warmer months.</li>
    <li><strong>Size:</strong> Choose a dog house that is spacious enough for your dog to comfortably stand, turn around, and lie down in.</li>
    <li><strong>Durable Materials:</strong> Opt for sturdy and weather-resistant materials such as wood or plastic to ensure the longevity of the dog house.</li>
  </ul>
  <h3>Types of Dog Houses</h3>
  <p>There are various types of dog houses available to suit different needs and preferences:</p>
  <ul>
    <li><strong>Traditional Wooden Dog House:</strong> Classic and durable, wooden dog houses offer timeless appeal and excellent insulation.</li>
    <li><strong>Plastic Dog House:</strong> Lightweight and easy to clean, plastic dog houses are ideal for smaller breeds and indoor/outdoor use.</li>
  </ul>
</div>
</body>
</html>
```
Football 
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Chennai Intercity Football Academy</title>
<link rel="stylesheet" href="des.css">
</head>
<body>
<div id="header">
  <h1>Chennai Intercity Football Academy</h1>
</div>
<div id="content">
  <h2>About the Academy</h2>
  <p>The Chennai Intercity Football Academy is committed to nurturing young talent and promoting the sport of football in the city.</p>
  <h3>Our Mission</h3>
  <p>Our mission is to provide quality coaching and training facilities to aspiring footballers, helping them reach their full potential both on and off the field.</p>
  <h3>Programs Offered</h3>
  <ul>
    <li>Youth Development Program</li>
    <li>Advanced Training Camps</li>
    <li>School Outreach Program</li>
    <li>Community Football Events</li>
  </ul>
  <h3>Facilities</h3>
  <p>Our state-of-the-art facilities include training grounds, fitness center, and classrooms for theoretical sessions.</p>
  <h3>Contact Us</h3>
  <p>For inquiries and registration, please contact us at info@chennaifootballacademy.com or call +91 1234567890.</p>
</div>
</body>
</html>
```
Hospital
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>MM Hospital</title>
<link rel="stylesheet" href="des.css">
</head>
<body>
<div id="header">
  <h1>MM Hospital</h1>
</div>
<div id="content">
  <h2>About MM Hospital</h2>
  <p>MM Hospital is a leading healthcare institution dedicated to providing quality medical care to the community.</p>
  <h3>Our Services</h3>
  <ul>
    <li>Emergency Care</li>
    <li>Inpatient Services</li>
    <li>Outpatient Services</li>
    <li>Specialty Clinics</li>
    <li>Diagnostic Services</li>
    <li>Surgical Services</li>
  </ul>
  <h3>Our Mission</h3>
  <p>Our mission is to improve the health and well-being of our community by providing compassionate, patient-centered care.</p>
  <h3>Our Vision</h3>
  <p>We strive to be a trusted healthcare partner, known for our commitment to excellence and innovation.</p>
</div>
</body>
</html>
```
Lake 
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Puzhal Lake</title>
<link rel="stylesheet" href="des.css">
</head>
<body>
<div id="header">
  <h1>Puzhal Lake</h1>
</div>
<div id="content">
  <h2>About Puzhal Lake</h2>
  <p>The Puzhal Lake, originally a small tank built during the British rule in Chennai (then named Madras), has undergone significant expansion and modifications over the years to serve as a crucial water source for the city.</p>
  <h3>History and Development</h3>
  <p>The reservoir, constructed in 1876, initially had a capacity of 500 million cubic feet (mcft) and featured two masonry weirs made of locally available laterite stones. These weirs served as surplus weirs to release excess water from the reservoir. In 1997, the storage capacity was increased to 3,300 mcft, and the depth was increased to 21.20 ft to meet the growing water demands of Chennai.</p>
  <h3>Key Features</h3>
  <ul>
    <li>The reservoir spans an area of approximately 7,600 acres.</li>
    <li>It features two masonry weirs, one measuring 178 m long and the other 220 m long.</li>
    <li>The bund surrounding the reservoir is 5 m high and extends for a distance of 7 km.</li>
    <li>Several villages and residential localities are situated around the reservoir.</li>
  </ul>
  <h3>Jones Tower</h3>
  <p>Constructed in 1881, Jones Tower serves to measure the depth of the lake water. The surrounding bund roads are popular among locals for recreational activities such as walking and running.</p>
  <h3>Water Seepage and Upgradation</h3>
  <p>In 2015, water seepage occurred due to heavy rainfall, prompting maintenance and repair efforts. Upgradation projects have also been undertaken, including strengthening the reservoir bund and enhancing filter arrangements.</p>
</div>
</body>
</html>

```
Design (css) : 
```
body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  
  #header {
    background-color: #4CAF50;
    color: #fff;
    text-align: center;
    padding: 20px 0;
  }
  
  #content {
    max-width: 800px;
    margin: 20px auto;
    padding: 0 20px;
  }
  
  h1 {
    color: #4CAF50;
    font-size: 24px;
  }
  
  h2 {
    color: #2E8B57;
    font-size: 20px;
  }
  
  h3 {
    color: #006400;
    font-size: 18px;
  }
  
  p {
    color: #333;
    line-height: 1.6;
  }
  
  ul {
    margin-bottom: 10px;
  }
  
```
## OUTPUT
##1
![Screenshot 2024-04-22 213030](https://github.com/VisHinu24/NearMe/assets/144244396/c5ae170e-489c-43d0-9d5a-362ffa894979)

##2
![Screenshot 2024-04-22 213038](https://github.com/VisHinu24/NearMe/assets/144244396/d862a62e-9d0c-4b08-a0f4-120ceac4f32e)

##3
![Screenshot 2024-04-22 213049](https://github.com/VisHinu24/NearMe/assets/144244396/192af182-4d57-44a0-9e3f-7553b15a4100)

##4
![Screenshot 2024-04-22 213058](https://github.com/VisHinu24/NearMe/assets/144244396/2c323292-daf6-425f-b213-d88441dde55f)

##5
![Screenshot 2024-04-22 213106](https://github.com/VisHinu24/NearMe/assets/144244396/e70109cd-04b8-4b4d-8d95-9c4aa7bb0b73)

##6

![Screenshot 2024-04-22 213112](https://github.com/VisHinu24/NearMe/assets/144244396/677cf4a1-0d20-4b31-a7be-359da486de2f)




## RESULT
The program for implementing image maps using HTML is executed successfully.
