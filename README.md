<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Boot Error Simulation</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: 'Courier New', Courier, monospace;
      font-size: 18px;
      padding: 50px;
    }
    .blink {
      animation: blink-animation 1s steps(2, start) infinite;
    }
    @keyframes blink-animation {
      to {
        visibility: hidden;
      }
    }
  </style>
</head>
<body>
  <pre>
Reboot and Select proper Boot device
or Insert Boot Media in selected Boot device and press a key

<span class="blink">_</span>
  </pre>
</body>
</html>
