---
title: Merchandise
layout: home
nav_order: 3
---
WIP
{: .label .label-green}

<div class="merch-page-section">
    <h1>All funds help our campaign!</h1>
    <div class="donate-section">
    <h2>Support Our Campaign</h2>
    <p>Select your donation amount:</p>
    <form action="/donate" method="POST" class="donation-form">
        <div class="donation-amounts">
            <label>
                <input type="radio" name="amount" value="5" required> $5
            </label>
            <label>
                <input type="radio" name="amount" value="20"> $20
            </label>
            <label>
                <input type="radio" name="amount" value="50"> $50
            </label>
            <label>
                <input type="radio" name="amount" value="100"> $100
            </label>
        </div>
        <button type="submit" class="donate-button">Donate Now</button>
    </form>
</div>
    <div class="merch-item-container">
        <!-- Shirt Item with Hover Effect -->
        <div class="merch-item">
            <img src="/product1.jpg" alt="T-Shirt Front" class="merch-image">
            <img src="/product1back.jpg" alt="T-Shirt Back" class="merch-image-hover">
        </div>   
        <!-- Other Merch Items -->
        <div class="merch-item">
            <img src="product2.jpg" alt="Cap" class="merch-image">
        </div>
        <div class="merch-item">
            <img src="product3.jpg" alt="Mug" class="merch-image">
        </div>
    </div>
</div>
<style>
    .merch-page-section {
        background-color: #f7f7f7;
        padding: 40px;
        text-align: center;
    }

    .merch-page-section h1 {
        font-size: 36px;
        margin-bottom: 30px;
        color: #333;
    }

    .merch-item-container {
        display: flex;
        justify-content: center;
        gap: 30px;
    }

    .merch-item {
        position: relative;
        width: 250px;
        height: 250px;
    }

    .merch-image {
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 10px;
        border: 2px solid #ddd;
        transition: opacity 0.3s ease;
    }

    /* Initially hide the back image */
    .merch-image-hover {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 10px;
        border: 2px solid #ddd;
        opacity: 0;
        transition: opacity 0.3s ease;
    }

    /* Show the back of the shirt on hover */
    .merch-item:hover .merch-image-hover {
        opacity: 1;
    }

    /* Hide the front of the shirt on hover */
    .merch-item:hover .merch-image {
        opacity: 0;
    }

    /* Style for the rest of the merch items */
    .merch-item img {
        width: 100%;
        height: auto;
        border-radius: 10px;
        border: 2px solid #ddd;
    }
        .donate-section {
        background-color: #f7f7f7;
        padding: 40px;
        text-align: center;
        border-radius: 10px;
        margin: 40px auto;
        max-width: 600px;
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    .donate-section h2 {
        color: #333;
        font-size: 2rem;
        margin-bottom: 20px;
    }

    .donate-section p {
        color: #666;
        font-size: 1.2rem;
        margin-bottom: 20px;
    }

    .donation-form {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .donation-amounts {
        display: flex;
        justify-content: center;
        gap: 20px;
        margin-bottom: 20px;
    }

    .donation-amounts label {
        background-color: #7095DB;
        color: white;
        padding: 10px 20px;
        border-radius: 5px;
        font-size: 1.2rem;
        cursor: pointer;
        transition: background-color 0.3s;
    }

    .donation-amounts input[type="radio"] {
        display: none;
    }

    .donation-amounts label:hover,
    .donation-amounts input[type="radio"]:checked + label {
        background-color: #4CAF50;
    }

    .donate-button {
        background-color: #4CAF50;
        color: white;
        padding: 15px 30px;
        border: none;
        border-radius: 5px;
        font-size: 1.2rem;
        cursor: pointer;
        transition: background-color 0.3s;
    }

    .donate-button:hover {
        background-color: #45a049;
    }

</style>


----