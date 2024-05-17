<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Migarkeleitor's Personal Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0F0F0F;
            color: #FFFFFF;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #1E1E1E;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        h1, h2 {
            text-align: center;
        }
        a {
            color: #00FF00;
            text-decoration: none;
        }
        .achievements {
            margin-top: 20px;
        }
        .games {
            margin-top: 20px;
            display: flex;
            flex-wrap: wrap;
        }
        .game {
            width: calc(33.33% - 20px);
            margin: 10px;
            padding: 10px;
            background-color: #333333;
            border-radius: 5px;
        }
        .game h3 {
            margin-top: 0;
        }
        .tetris-container {
            text-align: center;
            margin-top: 20px;
        }
        iframe {
            width: 100%;
            max-width: 400px;
            height: 600px;
            border: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Migarkeleitor's Personal Page</h1>
        <p>Welcome to my personal webpage! I'm Migarkeleitor, and I'm passionate about video games.</p>
        
        <h2>About Me</h2>
        <p>I'm a dedicated gamer who loves to challenge myself and achieve greatness in the virtual world.</p>
        
        <h2>Links</h2>
        <ul>
            <li><a href="#">Gaming Profile</a></li>
            <li><a href="#">Social Media</a></li>
            <li><a href="#">Contact Me</a></li>
        </ul>

        <h2>Achievements</h2>
        <div class="achievements">
            <p>Here are some of my proudest gaming achievements:</p>
            <ul>
                <li>Completed Dark Souls without dying</li>
                <li>Reached Grandmaster in Overwatch</li>
                <li>Won a Fortnite tournament</li>
                <li>100% completion in The Legend of Zelda: Breath of the Wild</li>
            </ul>
        </div>

        <h2>Played Games</h2>
        <div class="games">
            <div class="game">
                <h3>Game Title 1</h3>
                <p>Description or thoughts about the game.</p>
            </div>
            <div class="game">
                <h3>Game Title 2</h3>
                <p>Description or thoughts about the game.</p>
            </div>
            <div class="game">
                <h3>Game Title 3</h3>
                <p>Description or thoughts about the game.</p>
            </div>
            <!-- Add more game divs as needed -->
        </div>

        <div class="tetris-container">
            <h2>Play Tetris</h2>
            <iframe src="https://tetris.com/play-tetris" title="Tetris" allow="fullscreen"></iframe>
        </div>
    </div>
</body>
</html>
