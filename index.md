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
        .image-box {
            flex: 1;
            height: 80%;
        }
        .image-box img {
            height: 100%;
            width: 100%;
            object-fit: cover;
            border-radius: 10px;
        }
        .text-box {
            flex: 1;
            background-color: rgba(128, 0, 128, 0.8); /* Purple box */
            padding: 20px;
            margin-left: 50px;
            border-radius: 10px;
            color: white;
            text-align: center;
        }
        h1 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        p {
            font-size: 18px;
            margin-bottom: 20px;
        }
        .buttons {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .button {
            background-color: white;
            color: purple;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            text-decoration: none;
            text-align: center;
        }
        .button:hover {
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
            <div class="buttons">
                <a href="#" class="button">Donate Now</a>
                <a href="#" class="button">Buy Merchandise</a>
            </div>
        </div>
    </div>
</body>
</html>

----

