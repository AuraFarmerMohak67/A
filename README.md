<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Game Playground</title>
    <style>
        body { font-family: sans-serif; background: #2c3e50; color: white; margin: 0; padding: 20px; }
        header { text-align: center; padding: 40px 0; }
        .grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); 
            gap: 20px; 
            max-width: 1200px; 
            margin: 0 auto; 
        }
        .game-card { 
            background: #34495e; 
            border-radius: 15px; 
            overflow: hidden; 
            transition: transform 0.2s;
            cursor: pointer;
            text-align: center;
            border: 3px solid transparent;
        }
        .game-card:hover { transform: scale(1.05); border-color: #3498db; }
        .game-thumb { width: 100%; height: 150px; background: #7f8c8d; display: flex; align-items: center; justify-content: center; }
        .game-title { padding: 15px; font-weight: bold; }
        a { text-decoration: none; color: inherit; }
    </style>
</head>
<body>

    <header>
        <h1>🎮 MY FREE GAMES</h1>
        <p>Choose a game to start playing!</p>
    </header>

    <div class="grid">
        <a href="https://poki.com" target="_blank">
            <div class="game-card">
                <div class="game-thumb">🕹️</div>
                <div class="game-title">Play on Poki</div>
            </div>
        </a>

        <a href="https://www.google.com/logos/2010/pacman10-i.html" target="_blank">
            <div class="game-card">
                <div class="game-thumb">🟡</div>
                <div class="game-title">Pac-Man</div>
            </div>
        </a>

        </div>

</body>
</html>
