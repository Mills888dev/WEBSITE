---
title: Home
layout: home
nav_order: 1
---

WIP
{: .label .label-yellow}

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Political Campaign</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
        }
        .container {
            display: flex;
            height: 100vh;
            align-items: center;
            justify-content: center;
        }
        .image-box, .text-box {
            flex: 1;
            max-width: 50%; /* Ensure the two boxes take up equal space */
            height: auto;
        }
        .image-box img {
            width: 100%;
            height: auto;
            object-fit: cover;
            border-radius: 10px;
        }
        .text-box {
            background-color: rgba(128, 0, 128, 0.8); /* Purple box */
            padding: 20px;
            margin-left: 20px;
            border-radius: 10px;
            color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        h1 {
            font-size: 2.5vw;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.5vw;
            margin-bottom: 20px;
        }
        .newsletter-form {
            display: flex;
            flex-direction: column;
            gap: 10px;
            align-items: center;
        }
        .input-field {
            padding: 10px;
            border: none;
            border-radius: 5px;
            width: 80%;
            max-width: 300px;
            font-size: 1.2vw;
        }
        .submit-button {
            background-color: white;
            color: purple;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.2vw;
            text-align: center;
            width: 80%;
            max-width: 300px;
        }
        .submit-button:hover {
            background-color: purple;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="image-box">
            <img src="HomePhoto.png" alt="Candidate Image"> <!-- Replace with your image path -->
        </div>
        <div class="text-box">
            <h1>Your Voice Matters</h1>
            <p>Prepare to vote for Miles this election!</p>
            <div class="newsletter-form">
                <input type="email" class="input-field" placeholder="Enter your email" required>
                <button class="submit-button">Sign Up for Newsletter</button>
            </div>
        </div>
    </div>
</body>
</html>
----

