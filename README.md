<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Volleyball</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #ffcc70, #ff8c42);
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #d35400;
            color: white;
            padding: 20px;
        }

        .content {
            padding: 30px;
        }

        img {
            width: 400px;
            max-width: 90%;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            margin-top: 20px;
        }

        .info {
            margin-top: 20px;
            font-size: 18px;
            color: #333;
        }

        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #d35400;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
        }

        button:hover {
            background-color: #a84300;
        }
    </style>
</head>
<body>

<header>
    <h1>🏐 Volleyball</h1>
</header>

<div class="content">
    <h2>About Volleyball</h2>
    <p class="info">
        Volleyball is a team sport where two teams of six players are separated by a net.
        The objective is to score points by grounding the ball on the opponent's court.
    </p>

    <!-- Volleyball Image -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Volleyball_game.jpg" alt="Volleyball Game">

    <br>
    <button onclick="showMessage()">Click Me!</button>
</div>

<script>
    function showMessage() {
        alert("Volleyball is fun and energetic! 🏐");
    }
</script>

</body>
</html>
