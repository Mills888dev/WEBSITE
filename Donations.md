<style>
    .merch-page-section {
        background-color: #27262b;
        padding: 40px;
        text-align: center;
    }
    .merch-page-section h1 {
        font-size: 36px;
        margin-bottom: 30px;
        color: white;
    }
    .merch-item-container {
        display: flex;
        justify-content: center;
        gap: 30px;
        border-top: 5px solid #4CAF50; /* Adds a green top border */
        padding-top: 20px; /* Adds space below the border */
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
    .merch-item:hover .merch-image-hover {
        opacity: 1;
    }
    .merch-item:hover .merch-image {
        opacity: 0;
    }
</style>
