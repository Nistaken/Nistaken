<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clickable Text Example</title>
  <style>
    .clickable-text {
      font-size: 36px;
      font-weight: bold;
      color: #ffffff;
      text-shadow: 2px 2px 5px rgba(255, 0, 0, 0.5); /* Kırmızı gölge */
      cursor: pointer;
      transition: color 0.3s ease;
    }

    .clickable-text:hover {
      color: #ff0000; /* Hover sırasında kırmızıya dönüşür */
    }
  </style>
</head>
<body style="background-color: #000000; text-align: center; padding-top: 100px;">

  <p class="clickable-text" onclick="window.location.href='https://www.youtube.com/watch?v=WbHGtGSwoGA&ab_channel=CentralCee'">
    Why don't I have any commits on GitHub?
  </p>

</body>
</html>
