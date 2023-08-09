<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Westside Deli - Food Delivery Service</title>
    <style>
        /* Base styles for both light and dark mode */
        body {
            font-family: 'Lilita One', Arial, sans-serif;
            font-size: 14px;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 100%;
            margin: 0 auto;
            padding: 10px;
            text-align: center;
            background-color: #ffffff; /* Set the background color to a light color */
        }

        .header {
            padding: 5px;
            color: #ffffff;
            background-color: #004aad;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            text-decoration: none;
            color: #ffffff;
        }

        .content-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .content {
            padding: 20px;
            color: #FFbd59 ;
            text-align: center;
            font-size: 28px; /* Increase the font size */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); /* Add a subtle text shadow */
        }

        .cta-button {
            display: block; /* Change from inline-block to block */
            position: relative; /* Add position relative for pseudo-element positioning */
            padding: 12px 40px; /* Increase the padding for a button-like appearance */
            margin: 20px auto; /* Center the CTA button */
            text-decoration: none;
            border-radius: 50px;
            border: 2px solid #004aad; /* Add a border to the button */
            background-color: #FFbd59; /* Set the CTA button color to the correct blue */
            color: #004aad;
            font-size: 18px; /* Increase the font size for better visibility */
            font-weight: bold;
            font-family: 'Glacial Indifference', Arial, sans-serif; /* Use Glacial Indifference font for CTA */
            box-shadow: 0px 4px 8px rgba(0, 74, 173, 0.2); /* Add a subtle shadow effect */
            transition: transform 0.2s ease-in-out; /* Add a smooth transition on hover */
        }

        .cta-button:hover {
            transform: scale(1.05); /* Increase the button size slightly on hover */
        }

        .blue-panel {
            padding: 20px;
            border-radius: 5px;
            margin-bottom: 40px; /* Increase margin between blue panel and footer */
            background-color: #004aad;
            color: #ffffff;
            font-family: 'Glacial Indifference', Arial, sans-serif; /* Use Glacial Indifference font for blue panel */
            text-align: center; /* Center-align the text inside the blue panel */
        }

        /* Dark mode styles */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #121212;
                color: #ffffff;
            }

            .header {
                background-color: #0d3e65;
            }

            .logo {
                color: #ffffff;
            }

            .content {
                color: #ffffff;
            }

            .cta-button {
                background-color: #FFbd59; /* Set the CTA button color to the correct blue */
                color: #FFbd59;
            }

            .footer {
                color: #ffffff;
            }

            .blue-panel {
                background-color: #0d3e65;
                color: #ffffff;
            }
        }

        /* Add the modified seesaw shake animation keyframes */
        @keyframes seesawShake {
            0% { transform: rotateZ(0deg); }
            10% { transform: rotateZ(3deg); }
            20% { transform: rotateZ(-3deg); }
            30% { transform: rotateZ(2deg); }
            40% { transform: rotateZ(-2deg); }
            50% { transform: rotateZ(0deg); }
            100% { transform: rotateZ(0deg); }
        }

    </style>
    <!-- Add the link to the "Lilita One" font -->
    <link href='https://fonts.googleapis.com/css?family=Lilita One' rel='stylesheet'>
    <!-- Add the link to the "Glacial Indifference" font -->
    <link href="https://fonts.cdnfonts.com/css/glacial-indifference-2" rel="stylesheet">
</head>
<body style="background-color: #ffffff;">
    <div class="container">
        <!-- Header -->
        <div class="header" style="padding: 5px; color: #ffffff; background-color: #004aad;">
            <!-- The logo image has been removed, add your own logo here -->
            <a href="http://www.takeawaysbury.co.uk" class="logo" style="font-size: 24px; font-weight: bold; text-decoration: none; color: #ffffff;">
                <img src="https://i.imgur.com/OLnDv5S.png" alt="Takeaways Bury Logo" style="max-width: 200px;">
            </a>
        </div>
        
        <!-- Main Content Container -->
        <div class="content-container">
            <div class="content" style="padding: 20px; color: #FFbd59; text-align: center;">
                <h1 style="margin-bottom: 20px; animation: pulseAnimation 2s infinite;">10 Secs ⏱️ 
                10 Clicks🖱️ 
                10/10 Food 🤤</h1>
                <!-- Image removed, you can add your own images here -->
                <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExdDg1eXNpdGV2NHprMW9zanVpZnFjdHliMnY4OGt5OWVzb2N4c3YzaCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/PhQ7g2cgBPaAa0qTe6/giphy.gif" alt="Delicious Food" style="max-width: 100%; display: block; margin: 20px auto;">
                <br>
                <br>
                <!-- Update the CTA button with your own text -->
                <a href="http://www.takeawaysbury.com" class="cta-button" style="display: block; padding: 12px 40px; margin: 10px auto 20px; text-decoration: none; border-radius: 50px; border: 2px solid #004aad; background-color: #FFbd59; color: #004aad; animation: seesawShake 2s infinite; font-size: 18px; font-weight: bold; font-family: 'Glacial Indifference', Arial, sans-serif; box-shadow: 0px 4px 8px rgba(0, 74, 173, 0.2); transition: transform 0.2s ease-in-out;">
                    Order Your 10/10 Food Now
                </a>
            </div>
            
            <!-- Blue Panel -->
            <div class="blue-panel" style="padding: 20px; border-radius: 5px; background-color: #004aad; color: #ffffff; font-family: 'Glacial Indifference', Arial, sans-serif; text-align: center;">
                <ul style="text-align: left; list-style-type: disc;">
                    <h2>About Us</h2>
                    <!-- Replace the placeholder list items with your content -->
                    <li>We Host Your Local Favourites 📲</li>
                    <li>We Run Regular Disocunts 💰</li>
                    <li>We Save You Money 💸</li>
                    <li>We Are More Committed Than Ever To Give You All What You Want 🎉</li>
                </ul>
            </div>
        </div>
        
        <!-- Footer -->
        <div class="footer" style="color: #999999; padding: 10px; text-align: center;">
            <p>Follow Us:</p>
            <!-- Social media and app store icons with public image URLs -->
            <a href="https://www.instagram.com/takeaways_bury">
                <img src="https://i.imgur.com/nzgdTRr.png" alt="Instagram" style="max-width: 30px; margin-right: 10px;">
            </a>
            <a href="https://www.facebook.com/TakeawaysBury">
                <img src="https://i.imgur.com/4Sps8X3.png" alt="Facebook" style="max-width: 30px; margin-right: 10px;">
            </a>
            <a href="https://apps.apple.com/us/app/takeaways-bury-order-online/id1617767502">
                <img src="https://i.imgur.com/FhvgkIp.png" alt="App Store" style="max-width: 30px; margin-right: 10px;">
            </a>
            <a href="https://play.google.com/store/apps/details?id=com.waan.takeawaysbury">
                <img src="https://i.imgur.com/L5aGiM8.png" alt="Play Store" style="max-width: 30px;">
            </a>
            <p>Contact us at: info@takeawaysbury.com</p>
        </div>
    </div>
</body>
</html>
