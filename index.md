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
        /* Wrapper to keep the top section at the top */
        .top-section {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            top: 0;
            z-index: 999;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .image-box, .text-box {
            flex: 1;
            max-width: 50%; /* Ensures the image and text take up equal space */
        }
        .image-box img {
            width: 100%;
            height: auto;
            object-fit: cover;
            border-radius: 10px;
        }
        .text-box {
            background-color: #1EB07F; /* Purple box */
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
            color: #1EB07F;
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
            background-color: #1EB07F;
            color: white;
        }
        /* Content below the top section */
        .below-content {
            padding: 40px;
            text-align: center;
            background-color: #fff;
        }
        .below-content h2 {
            font-size: 28px;
            color: #333;
        }
                .donate-bar {
            background-color: #53D4E6; /* Solid color (Green in this case) */
            color: white;
            padding: 20px;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 999;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }
        .donate-bar h2 {
            margin: 0;
            margin-right: 20px;
            font-size: 24px;
        }
        .donate-bar a {
            background-color: white;
            color: #4CAF50;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .donate-bar a:hover {
            background-color: #45a049;
            color: white;
        }
                .merch-section {
            padding: 40px;
            text-align: center;
        }
        .merch-section h2 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #333;
        }
        .merch-preview {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 20px;
        }
        .merch-preview img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            border: 2px solid #ddd;
        }
        .merch-section a {
            background-color: #333;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
        }
        .merch-section a:hover {
            background-color: #555;
        }
    </style>
</head>
    <div class="top-section">
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
    <div class="below-content">
        </div>
        <div class="merch-section">
        <h2>Check Out Our Merchandise</h2>
        <div class="merch-preview">
            <img src="product1.jpg" alt="T-Shirt">  <!-- Replace with actual image paths -->
            <img src="product2.jpg" alt="Cap">
            <img src="product3.jpg" alt="Mug">
        </div>
        <a href="/merch">Visit Our Merch Page</a>
        </div>
      <div class="donate-bar">
        <h2>Donate Now</h2>
        <a href="/Funding/Donations.md">Go to Donations Page</a>
        </div>
</html>

