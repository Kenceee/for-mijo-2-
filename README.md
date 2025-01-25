<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f8ff;
            padding: 50px;
        }
        .flower-bouquet {
            display: none;
            margin-top: 20px;
        }
        .button {
            background-color: #ff69b4;
            color: white;
            padding: 15px 25px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <h1>Happy Birthday Pre!</h1>
    <p>Click mo yung button hehe</p>
    <button class="button" onclick="revealSurprise()">Click me!</button>
    
    <div class="flower-bouquet" id="bouquet">
        <img src="white.jpeg" alt="Flower Bouquet" width="300">
        <p style="font-size: 20px; color: #ff1493;">Here’s a White rose bouquet just for you, kase you’re the white rose in my heart’s garden.:</p>
        
    </div>

    <script>
        function revealSurprise() {
            document.getElementById('bouquet').style.display = 'block';
        }
    </script>
</body>
</html>
