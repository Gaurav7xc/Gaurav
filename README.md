<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Photo Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            margin: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            transition: transform 0.3s;
            cursor: pointer;
        }

        .gallery img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Photo Gallery</h1>
    </header>

    <div class="gallery">
        <!-- Add your image elements here with respective information -->
        <img src="your-image-1.jpg" alt="Description 1">
        <img src="your-image-2.jpg" alt="Description 2">
        <!-- Add more images as needed -->
    </div>

</body>
</html>
