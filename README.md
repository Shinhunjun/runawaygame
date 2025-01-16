<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Make Jimin More - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
            margin: 20px;
        }
        h1, h2 {
            color: #555;
        }
        pre {
            background: #eee;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        code {
            color: #d14;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Make Jimin More</h1>
    <p>
        <strong>Make Jimin More</strong> is a survival game where you control two hearts to avoid the enemy, Jimin. 
        Use <code>WASD</code> and <code>arrow keys</code> to move both hearts and survive as long as possible!
    </p>

    <h2>Game Features</h2>
    <ul>
        <li><strong>Dual Control:</strong> Strategically maneuver two hearts to avoid collisions with Jimin.</li>
        <li><strong>Increasing Difficulty:</strong> More Jimin characters appear over time, moving faster as the game progresses.</li>
        <li><strong>Simple and Addictive Gameplay:</strong> Easy-to-learn controls with challenging gameplay.</li>
        <li><strong>Charming Graphics:</strong> The hearts and Jimin are visually appealing and fun.</li>
    </ul>

    <h2>Installation and Running the Game</h2>

    <h3>Requirements</h3>
    <ul>
        <li>Python 3.8 or higher</li>
        <li>Pygame (latest <code>pygame-ce</code> recommended)</li>
    </ul>

    <h3>Installation</h3>
    <ol>
        <li><strong>Clone the repository:</strong>
            <pre><code>git clone https://github.com/username/make-jimin-more.git
cd make-jimin-more</code></pre>
        </li>
        <li><strong>Install dependencies:</strong>
            <pre><code>pip install pygame-ce</code></pre>
        </li>
        <li><strong>Check assets:</strong> Ensure the <code>assets</code> folder contains the following files:
            <ul>
                <li><code>background.png</code>: Background image of the game</li>
                <li><code>heart.png</code>: Player heart image</li>
                <li><code>enemy_face.png</code>: Jimin character image</li>
            </ul>
        </li>
    </ol>

    <h3>Run the Game</h3>
    <pre><code>python main.py</code></pre>
</body>
</html>
