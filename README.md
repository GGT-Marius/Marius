
<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GGT Hytte</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: url('https://source.unsplash.com/1600x900/?forest,trees') no-repeat center center/cover;
            text-align: center;
            color: white;
        }
        .container {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: rgba(0, 0, 0, 0.5);
        }
        h1 {
            font-size: 5rem;
            font-style: italic;
            font-weight: bold;
            text-shadow: 3px 3px 10px rgba(0,0,0,0.7);
            background: linear-gradient(45deg, #ffdd00, #ff6600);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .info {
            margin-top: 20px;
            font-size: 1.5rem;
            max-width: 600px;
        }
        .button {
            margin-top: 30px;
            padding: 15px 30px;
            font-size: 1.5rem;
            color: white;
            background: #4CAF50;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            text-decoration: none;
        }
        .button:hover {
            background: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>GGT HYTTE</h1>
        <p class="info">Velkommen til GGT – en koselig hytte i Kristiansand.</p>
        <p class="info">Hytta ble bygget i mars 2025 av syv personer født i 2010.</p>
        <a href="page1.html" class="button">Bli med</a>
    </div>
</body>
</html>
