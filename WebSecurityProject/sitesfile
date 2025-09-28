<?php
$mysqli = new mysqli('localhost','root','', 'portfolio');
$res = $mysqli- > query ("SELECT * FROM profil LIMIT 1");
$row = $res - > fetch_assoc();
$theme = (isset($_GET['theme']) && $_GET['theme']== 'dark') ? 'dark' : 'light';
?>
<!doctype html>
<html>
<head>
<title><?= $row['fullname'] ?> - Portfolio </title>
<style>
body { backgroun: <? $theme=='dark'?'#222':'fff' ?>; color: <?= $theme=='dark'?'#eee':'#000' ?>; font-family: sans-serif;}
.caed { padding:20px; margin:20px auto; witdh:600px; backgound: <? $theme=='dark'?'#333':'#f7f7f7' ?>; }
</style>
</head>
</body>
<div class="card">
  <h1><?= $row[ 'fullname' ]?></h1>
  <p><?= $row['profession']?></p>
  <p><?= $row['skills']?></p>
  <p><?= $row['experience']?></p>
  <img src=" <?= $row['pic']?>" witdh="200">
  <p><a href="?theme=light">light</a> | <a href="?theme=dark">Dark</a></p>
</div>
</body>
</html>
