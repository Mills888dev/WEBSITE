---
title: Merchandise
layout: home
nav_order: 3
---
WIP
{: .label .label-green}

<div class="merch-page-section">
    <h1>Our Merchandise</h1>
    <div class="merch-item-container">
        <!-- Shirt Item with Hover Effect -->
        <div class="merch-item">
            <img src="shirt-front.jpg" alt="T-Shirt Front" class="merch-image">
            <img src="shirt-back.jpg" alt="T-Shirt Back" class="merch-image-hover">
        </div>
        
        <!-- Other Merch Items -->
        <div class="merch-item">
            <img src="cap.jpg" alt="Cap" class="merch-image">
        </div>
        <div class="merch-item">
            <img src="mug.jpg" alt="Mug" class="merch-image">
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
</style>


----