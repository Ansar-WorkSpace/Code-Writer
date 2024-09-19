# Code-Writer
Here can write multiple language code at one place like write altogether- HTML,CSS and JavaScript


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script src="https://kit.fontawesome.com/f97427a625.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="style.css">
  <title>Document</title>
</head>
<body>
  <div class="wrapper">
    <div class="input">
      <div class="editor">
        <label><i class="fa-brands fa-html5"></i> HTML</label>
        <textarea class="html" onkeyup="compileCode()" spellcheck="false"></textarea>
      </div>
      <div class="editor">
        <label><i class="fa-brands fa-css3-alt"></i> CSS</label>
        <textarea class="css" onkeyup="compileCode()" spellcheck="false"></textarea>
      </div>
      <div class="editor">
        <label><i class="fa-brands fa-square-js"></i> JavaScript</label>
        <textarea class="javascript" onkeyup="compileCode()" spellcheck="false"></textarea>
      </div>
    </div>

    <div class="output">
      <label><i class="fa-solid fa-play"></i> Result</label>
      <iframe class="display"></iframe>
    </div>
  </div>
</body>

<script src="script.js"></script>
</html>
