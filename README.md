<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Button Message</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background: #ffb6c1; /* pinkish background */
      font-family: Arial, sans-serif;
    }

    button {
      padding: 12px 24px;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      background-color: #ff69b4;
      color: white;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: #ff1493;
    }

    #message {
      margin-top: 20px;
      font-size: 22px;
      font-weight: bold;
      color: #d63384;
      display: none;
    }
  </style>
</head>
<body>

  <button onclick="showMessage()">Click Me 💖</button>
  <div id="message">Sorryyy Merii Motii comee ! 😊</div>

  <script>
    function showMessage() {
      document.getElementById("message").style.display = "block";
    }
  </script>

</body>
</html>
