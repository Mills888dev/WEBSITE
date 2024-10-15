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
            font-size: 16px;
        }
        .submit-button {
            background-color: white;
            color: purple;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
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
            <img src="candidate.jpg" alt="Candidate Image"> <!-- Replace with your image path -->
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

