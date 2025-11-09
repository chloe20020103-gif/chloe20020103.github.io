# chloe20020103.github.io
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>My Github Page</title>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <style>
    body { font-family: Arial; text-align: center; margin-top: 50px; }
    #message { color: blue; font-size: 20px; }
  </style>
</head>
<body>
  <h1>Welcome to My Github Page</h1>
  <button id="btn">Click Me</button>
  <p id="message"></p>

  <script>
    $("#btn").click(function(){
      $("#message").text("Hello! jQuery is working!");
    });
  </script>
</body>
</html>
