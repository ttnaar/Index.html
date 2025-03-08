<!DOCTYPE html><html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Я люблю тебя!</title>
    <style>
        body {
            background-color: pink;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        h1 {
            color: red;
            font-size: 50px;
            margin-top: 20vh;
        }
        .hearts {
            font-size: 100px;
            animation: float 2s infinite alternate;
        }
        @keyframes float {
            from { transform: translateY(0); }
            to { transform: translateY(-20px); }
        }
    </style>
</head>
<body>
    <h1>Я ❤️ Тебя!</h1>
    <div class="hearts">❤️❤️❤️</div>
</body>
</html>
