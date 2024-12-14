#Gaming
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaming Theme</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
        }
        header {
            background: #1a1a1a;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.5);
        }
        header h1 {
            color: #ff4500;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            color: #ff4500;
        }
        .banner {
            background: url('https://via.placeholder.com/1920x600') center/cover no-repeat;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .banner h2 {
            color: #fff;
            font-size: 50px;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.7);
        }
        .section {
            padding: 20px;
            text-align: center;
        }
        .section h2 {
            color: #ff4500;
            margin-bottom: 20px;
        }
        .games {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }
        .game-card {
            background: #1a1a1a;
            width: 300px;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.7);
        }
        .game-card img {
            max-width: 100%;
            border-radius: 5px;
        }
        .game-card h3 {
            margin: 15px 0;
        }
        footer {
            background: #1a1a1a;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gaming World</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Games</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <div class="banner">
        <h2>Welcome to Gaming World</h2>
    </div>

    <section class="section">
        <h2>Featured Games</h2>
        <div class="games">
            <div class="game-card">
                <img src="https://via.placeholder.com/300x200" alt="Game 1">
                <h3>Game Title 1</h3>
                <p>A thrilling action-adventure game.</p>
            </div>
            <div class="game-card">
                <img src="https://via.placeholder.com/300x200" alt="Game 2">
                <h3>Game Title 2</h3>
                <p>An exciting multiplayer experience.</p>
            </div>
            <div class="game-card">
                <img src="https://via.placeholder.com/300x200" alt="Game 3">
                <h3>Game Title 3</h3>
                <p>An immersive RPG adventure.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Gaming World. All rights reserved.</p>
    </footer>
</body>
</html>
