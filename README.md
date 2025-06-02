# Guess-Where-I-Moved
Drag and drop me to the place you think I moved
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Guess Where I Moved!</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>Guess Where I Moved!</h1>
  <p>Drag the marker onto the correct state.</p>
  <div id="game-container">
    <img src="map.png" alt="Map" id="map" />
    <img src="marker.png" alt="You" id="marker" draggable="true" />
  </div>
  <p id="result"></p>

  <script src="script.js"></script>
</body>
</html>
