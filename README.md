# Ex04 Places Around Me
# Date: 05/10/2024
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

# CODE:-

# index.html:-

    <html>
        <head>

            <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Alegreya:ital,wght@0,400..900;1,400..900&display=swap" rel="stylesheet">
            
            <title>Image map</title>
            <style>
                #head h1{
                    position: absolute;
                    top: px;
                    left: 590px;
                    font-family: "Alegreya", serif;
                    font-size: 75px;

                }
                #map img{
                    position: absolute;
                    top: 200px;
                    left: 60px;
                    width:1400px;
                    height: 800px;
                }
                #space{
                    top: 1000px;
                    position: absolute;
                    width: 1500px;
                    height: 100px;
                }
                #titan{
                    position:absolute;
                    top:50px;
                    left: 200px;


                }
            </style>
        </head>
        <body>
            <div id="head">
                <h1>Porur Map</h1>
            </div>
            <div id="titan">
                <img src="Titan eye plus.png">
            </div>

            <div id="map">
                            
                <img src="WhatsApp Image 2024-12-07 at 19.21.33.jpeg" usemap="#image-map">

                <map name="image-map">
                    <area target="" alt="AB's Restaurant" title="" href="Saravana stores.html" coords="581,630,553,615,565,576,602,562,647,571,639,622,617,630,606,632" shape="poly">
                    <area target="" alt="Poorvika" title="" href="Poorvika mobiles.html" coords="592,273,632,258,705,262,714,352,602,334,580,312" shape="poly">
                    <area target="" alt="HDFC Bank" title="" href="HDFC Bank.html" coords="816,201,868,184,892,236,857,249,844,233" shape="poly">
                    <area target="" alt="Super Saravana Stores" title="" href="AB's Barbecues Restaurant.html" coords="538,137,590,70,710,93,721,200,587,197" shape="poly">
                </map>

            </div>
            <div id="space">

            </div>
            
        </body>
    </html>
    <img src="image.jpeg" usemap="#image-map">

# POORVIKA:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Poorvika Mobiles</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
        <style>
            /* General reset */
            body {
                margin: 0;
                padding: 0;
                font-family: 'Roboto', sans-serif;
                background-color: #f4f4f9;
                color: #333;
            }

            /* Header styles */
            header {
                background-color: #2d89ef;
                color: white;
                padding: 20px 0;
                text-align: center;
            }

            header h1 {
                margin: 0;
                font-size: 2.5em;
                font-weight: 700;
            }

            /* Logo section */
            #logo {
                text-align: center;
                margin: 30px 0;
            }

            #logo img {
                max-width: 80%;
                height: auto;
                border-radius: 10px;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            }

            /* About section */
            #about {
                padding: 40px 20px;
                max-width: 1200px;
                margin: 50px auto;
                background-color: #ffffff;
                border-radius: 10px;
                box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            }

            #about h1 {
                font-size: 2.2em;
                font-weight: 700;
                margin-bottom: 20px;
                color: #2d89ef;
            }

            #about p {
                font-size: 1.2em;
                line-height: 1.8;
                color: #555;
                margin: 0;
            }

            /* Footer */
            footer {
                background-color: #333;
                color: white;
                text-align: center;
                padding: 15px 0;
                margin-top: 50px;
            }

            footer p {
                margin: 0;
                font-size: 0.9em;
            }

            footer a {
                color: #2d89ef;
                text-decoration: none;
                font-weight: 700;
            }

            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <header>
            <h1>Poorvika Mobiles</h1>
        </header>

        <div id="logo">
            <img src="{% static 'map/poorvika_logo.png' %}" alt="Poorvika Logo">
        </div>

        <div id="about">
            <h1>About Us</h1>
            <p>
                Poorvika Mobiles Private Limited is India’s leading mobile retailer, with its wings wide spread across South India and a reputation extending nationwide. Poorvika offers mobile phones & tablets from domestic and international brands, along with accessories, data cards, earphones, smartwatches, and more. Driven by the mantra **“Think Mobile, Think Poorvika”**, we bring customers top-notch service and affordable quality.
                <br><br>
                Poorvika is headquartered in Chennai, India, with a strong presence in Tamil Nadu, Pondicherry, Kerala, Karnataka, and Maharashtra. Beyond mobile sales, we provide exceptional after-sales service and gadgets that redefine convenience. Poorvika Mobiles is your trusted partner for affordable pricing, quality products, and a customer-first approach, which has solidified our reputation as India’s premier mobile retai
            </p>
        </div>

# SARAVANA:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Saravana Stores Porur</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
        <style>
            /* General Reset */
            body {
                margin: 0;
                padding: 0;
                font-family: 'Open Sans', sans-serif;
                background-color: #f9f9f9;
                color: #333;
            }

            /* Header styles */
            header {
                background-color: #f05454;
                color: white;
                padding: 20px 0;
                text-align: center;
            }

            header h1 {
                margin: 0;
                font-size: 2.5em;
                font-weight: 600;
            }

            /* Logo Section */
            #logo {
                text-align: center;
                margin: 30px 0;
            }

            #logo img {
                max-width: 80%;
                height: auto;
                border-radius: 5px;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            }

            /* About Section */
            #about {
                padding: 40px 20px;
                max-width: 1200px;
                margin: 50px auto;
                background-color: #ffffff;
                border-radius: 10px;
                box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            }

            #about h1 {
                font-size: 2.2em;
                font-weight: 600;
                margin-bottom: 20px;
                color: #f05454;
            }

            #about p {
                font-size: 1.2em;
                line-height: 1.8;
                color: #555;
                margin: 0;
            }

            /* Footer */
            footer {
                background-color: #333;
                color: white;
                text-align: center;
                padding: 15px 0;
                margin-top: 50px;
            }

            footer p {
                margin: 0;
                font-size: 0.9em;
            }

            footer a {
                color: #f05454;
                text-decoration: none;
                font-weight: 600;
            }

            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <header>
            <h1>Saravana Stores Porur</h1>
        </header>

        <div id="logo">
            <img src="{% static 'map/Saravana_logo.jpeg' %}" alt="Saravana Stores Logo">
        </div>

        <div id="about">
            <h1>About Us</h1>
            <p>
                Saravana Stores, established in 1969, is a premier retail chain in India and the largest family-owned business of its kind. Renowned for introducing the **Aadi Thallupadi sale** concept, Saravana Stores represents a success story built on hard work, sound business practices, and visionary leadership.
                <br><br>
                Located across T. Nagar, Purasawalkam, Chrompet, and Porur, Saravana Stores offers a delightful shopping experience. It is a one-stop shopping destination offering a vast range of products, from textiles and jewelry to home appliances and groceries, catering to the needs of every family member.
                <br><br>
                With unbeatable prices and an extensive variety of items, Saravana Stores continues to uphold its commitment to quality and customer satisfaction. Whether you are shopping for clothing, accessories, or electronics, Saravana Stores is your trusted choice.
            </p>
        </div>

        <footer>
            <p>&copy; 2024 Saravana Stores Porur | <a href="{% url 'index' %}">Back to Map</a></p>
        </footer>
    </body>
    </html>

# HDFC:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HDFC Bank</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
        <style>
            /* General reset */
            body {
                margin: 0;
                padding: 0;
                font-family: 'Open Sans', sans-serif;
                background-color: #f4f4f9;
                color: #333;
            }

            /* Header styles */
            header {
                background-color: #0033a1;
                color: white;
                padding: 20px 0;
                text-align: center;
            }

            header h1 {
                margin: 0;
                font-size: 2.5em;
                font-weight: 600;
            }

            /* Logo section */
            #logo {
                text-align: center;
                margin: 30px 0;
            }

            #logo img {
                max-width: 300px;
                height: auto;
                border-radius: 5px;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            }

            /* About section */
            #about {
                padding: 40px 20px;
                max-width: 1200px;
                margin: 50px auto;
                background-color: #ffffff;
                border-radius: 10px;
                box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            }

            #about h1 {
                font-size: 2.2em;
                font-weight: 600;
                margin-bottom: 20px;
                color: #0033a1;
            }

            #about p {
                font-size: 1.2em;
                line-height: 1.8;
                color: #555;
                margin: 0;
            }

            /* Footer */
            footer {
                background-color: #333;
                color: white;
                text-align: center;
                padding: 15px 0;
                margin-top: 50px;
            }

            footer p {
                margin: 0;
                font-size: 0.9em;
            }

            footer a {
                color: #0033a1;
                text-decoration: none;
                font-weight: 600;
            }

            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <header>
            <h1>Welcome to HDFC Bank</h1>
        </header>

        <div id="logo">
            <img src="{% static 'map/hdfc_Logo.png' %}" alt="HDFC Bank Logo">
        </div>

        <div id="about">
            <h1>About Us</h1>
            <p>
                The Housing Development Finance Corporation Limited (HDFC) was one of the first financial institutions in India to receive an “in principle” approval from the Reserve Bank of India (RBI) to establish a private sector bank. This landmark move was part of RBI’s policy to liberalize the Indian banking industry in 1994.
                <br><br>
                Incorporated in August 1994, HDFC Bank began operations in January 1995 as a Scheduled Commercial Bank. With its registered office in Mumbai, India, HDFC Bank has since emerged as a leader in the banking industry, offering innovative financial solutions, unparalleled customer service, and a commitment to excellence.
            </p>
        </div>

        <footer>
            <p>&copy; 2024 HDFC Bank | <a href="{% url 'index' %}">Back to Map</a></p>
        </footer>
    </body>
    </html>

# RESTAURANT:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>AB's Absolute Barbecues Restaurant</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
        <style>
            /* General reset */
            body {
                margin: 0;
                padding: 0;
                font-family: 'Poppins', sans-serif;
                background-color: #f9f9f9;
                color: #333;
            }

            /* Header styles */
            header {
                background-color: #f78c1f;
                color: white;
                padding: 20px 0;
                text-align: center;
            }

            header h1 {
                margin: 0;
                font-size: 2.5em;
                font-weight: 600;
            }

            /* Logo section */
            #logo {
                text-align: center;
                margin-top: 30px;
            }

            #logo img {
                max-width: 200px;
                border-radius: 15px;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            }

            /* About section */
            #about {
                padding: 40px 20px;
                max-width: 1200px;
                margin: 50px auto;
                background-color: #ffffff;
                border-radius: 10px;
                box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            }

            #about h1 {
                font-size: 2.2em;
                font-weight: 600;
                margin-bottom: 20px;
                color: #f78c1f;
            }

            #about p {
                font-size: 1.2em;
                line-height: 1.8;
                color: #555;
            }

            /* Footer */
            footer {
                background-color: #333;
                color: white;
                text-align: center;
                padding: 15px 0;
                margin-top: 50px;
            }

            footer p {
                margin: 0;
                font-size: 0.9em;
            }

            footer a {
                color: #f78c1f;
                text-decoration: none;
                font-weight: 600;
            }

            footer a:hover {
                text-decoration: underline;
            }
        </style>
    </head>
    <body>
        <header>
            <h1>Welcome to Absolute Barbecues</h1>
        </header>

        <div id="logo">
            <img src="{% static 'map/ab_logo.png' %}" alt="AB's Logo">
        </div>

        <div id="about">
            <h1>About Us</h1>
            <p>
                Absolute Barbecues was born from pure passion. It begins with barbecues, and with it comes the idea of celebration. In fact, they are inseparable. 
                This is a place where people can have a blast without limits. <br><br>
                A buffet restaurant specializing in barbecue varieties, Indian cuisine, exotic meats, continental specials, and drool-worthy desserts. 
                It's a place where you can come with your family and friends and have a gala time, every day of the week, if you so wish. <strong>That’s Absolute Barbecues.</strong>
            </p>
        </div>

        <footer>
            <p>&copy; 2024 Absolute Barbecues | <a href="{% url 'index' %}">Back to Map</a></p>
        </footer>
    </body>
    </html>


# OUTPUT:-
![Result](1.png)

# POORVIKA:
!['Result'](poorvika.png)

# HDFC:
!['Result'](hdfc.png)

# SARAVANA:
!['Result'](saravana.png)

# RESTAURANT:
!['Restaurant'](abc.png)
# RESULT
The program for implementing image maps using HTML is executed successfully.
