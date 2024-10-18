---
title: Taxes
layout: home
nav_exclude: true
---
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oops! Wrong Turn</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f7f7f7;
        }

        .container {
            text-align: center;
            background-color: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 3rem;
            color: #ff6347;
        }

        p {
            font-size: 1.5rem;
            margin: 20px 0;
        }

        .joke {
            font-size: 1.2rem;
            margin: 20px 0;
            color: #555;
        }

        .back-home-button {
            display: inline-block;
            background-color: #4CAF50;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 10px;
            font-size: 1.2rem;
            transition: background-color 0.3s;
        }

        .back-home-button:hover {
            background-color: #45a049;
        }

        .emoji {
            font-size: 4rem;
        }

        /* Responsive design */
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }

            p, .joke {
                font-size: 1.1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Oops! Wrong Turn!</h1>
        <span class="emoji">🤔</span>
        <p>Looks like you've wandered off the map...</p>
        <div class="joke">
            <strong>Why did the web developer go broke?</strong><br>
            <em>Because he used up all his cache!</em>
        </div>
        <a href="/index.md" class="back-home-button">Take Me Home</a>
    </div>
</body>
</html>