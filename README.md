
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Simple Pong</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="wrapper">
    <h1>Simple Pong</h1>
    <p class="instructions">Controls: Move the mouse over the game or use Arrow Up / Arrow Down to move the left paddle.</p>
    <div class="scoreboard">
      <div class="score player-score" id="playerScore">0</div>
      <div class="score computer-score" id="computerScore">0</div>
    </div>
    <canvas id="game" width="800" height="500"></canvas>
    <div class="controls">
      <button id="restartBtn">Restart</button>
    </div>
    <p class="footer">First to 10 wins. Built with HTML, CSS & JavaScript.</p>
  </div>

  <script src="script.js"></script>
</body>
</html>
