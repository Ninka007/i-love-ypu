# i-love-you

[index.html](https://github.com/user-attachments/files/23341518/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>I love u Cheryl</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>I love u Cheryl</h1>
  <div class="heart">❤</div>
</body>
</html>



[style.css](https://github.com/user-attachments/files/23341520/style.css)body {
  background: #0b1220;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  font-family: Arial, sans-serif;
  flex-direction: column;
}

h1 {
  color: #ff6b81;
  font-size: 48px;
  animation: pulse 1s infinite;
}

.heart {
  color: #ff6b81;
  font-size: 60px;
  animation: beat 1s infinite;
  margin-top: 10px;
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.2); }
}

@keyframes beat {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.3); }
}

