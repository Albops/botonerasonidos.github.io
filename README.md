<html>
<head>
  <title>Botonera de sonidos</title>
  <style>
    /* CSS styles for buttons */
    .numbered-button {
      font-size: 24px; /* set the font size */
      width: 100px; /* set the width */
      height: 60px; /* set the height */
      margin: 5px; /* add margin between buttons */
      color: #fff; /* set the text color */
      border: none; /* remove button borders */
      border-radius: 5px; /* add border radius for rounded edges */
    }

    /* Custom background colors for each button */
    #button1 {
      background-color: #3498db; /* blue */
    }

    #button2 {
      background-color: #2ecc71; /* green */
    }

    #button3 {
      background-color: #e74c3c; /* red */
    }

    #button4 {
      background-color: #9b59b6; /* purple */
    }

    #button5 {
      background-color: #f39c12; /* orange */
    }

    #button6 {
      background-color: #1abc9c; /* teal */
    }

    #button7 {
      background-color: #d35400; /* dark orange */
    }

    #button8 {
      background-color: #27ae60; /* dark green */
    }

    #button9 {
      background-color: #8e44ad; /* dark purple */
    }

    #button10 {
      background-color: #f1c40f; /* yellow */
    }

    #button11 {
      background-color: #2c3e50; /* dark blue */
    }

    #button12 {
      background-color: #e67e22; /* bright orange */
    }

    #button13 {
      background-color: #c0392b; /* dark red */
    }

    #button14 {
      background-color: #8e44ad; /* dark purple */
    }

    #button15 {
      background-color: #3498db; /* blue */
    }
  </style>
  <script>
    var currentAudio = null;

    // JavaScript code to play or pause sounds when buttons are clicked
    function playOrPauseSound(soundFile) {
      if (currentAudio !== null && !currentAudio.paused) {
        currentAudio.pause();
      }

      if (currentAudio !== soundFile) {
        currentAudio = new Audio(soundFile);
        currentAudio.play();
      } else {
        currentAudio = null;
      }
    }
  </script>
</head>
<body>
  <h1>Botonera de sonidos</h1>
  
  <div>
    <h3>1</h3>
    <button id="button1" class="numbered-button" onclick="playOrPauseSound('Apple crunch sound effect.mp3')">1</button>
    <button id="button2" class="numbered-button" onclick="playOrPauseSound('Leaves  branches sound effect.mp3')">2</button>
    <button id="button3" class="numbered-button" onclick="playOrPauseSound('Human EatingCrunch Sound Effect HD.mp3')">3</button>
  </div>
  
  <div>
    <h3>2</h3>
    <button id="button4" class="numbered-button" onclick="playOrPauseSound('GooeySlime  Sound Effect.mp3')">4</button>
    <button id="button5" class="numbered-button" onclick="playOrPauseSound('Bubble Sound Effect.mp3')">5</button>
    <button id="button6" class="numbered-button" onclick="playOrPauseSound('Woodpecker  Sound Effect.mp3')">6</button>
  </div>
  
  <div>
    <h3>3</h3>
    <button id="button7" class="numbered-button" onclick="playOrPauseSound('Woodpecker  Sound Effect.mp3')">7</button>
    <button id="button8" class="numbered-button" onclick="playOrPauseSound('Leaves  branches sound effect.mp3')">8</button>
    <button id="button9" class="numbered-button" onclick="playOrPauseSound('Sweet Bird Sound  Morning Sound Effect  Garden Bird.mp3')">9</button>
  </div>
  
  <div>
    <h3>4</h3>
    <button id="button10" class="numbered-button" onclick="playOrPauseSound('Acoustic Guitar G Major Chord Sound Effect.mp3')">10</button>
    <button id="button11" class="numbered-button" onclick="playOrPauseSound('Acoustic Guitar A Minor Chord Sound Effect.mp3')">11</button>
    <button id="button12" class="numbered-button" onclick="playOrPauseSound('Sweet Bird Sound  Morning Sound Effect  Garden Bird.mp3')">12</button>
  </div>
  
  <div>
    <h3>5</h3>
    <button id="button13" class="numbered-button" onclick="playOrPauseSound('Sharp Noise Sound Effect.mp3')">13</button>
    <button id="button14" class="numbered-button" onclick="playOrPauseSound('GooeySlime  Sound Effect.mp3')">14</button>
    <button id="button15" class="numbered-button" onclick="playOrPauseSound('Bubble Sound Effect.mp3')">15</button>
  </div>
  
</body>
</html>






