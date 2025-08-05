<!DOCTYPE html>
# Hello there!
I'm Quark a developer that creates stuff.


<html>
<head>
<title>Quark's Page</title>
</head>
<body>

<html>
<head>
</head>
<body>
<button onclick="openGame()">Open Game</button>
<script>
function openGame() {
var win = window.open()
var url = "https://clever.com"
var iframe = win.document.createElement('iframe')
iframe.style.width = "100%";
iframe.style.height = "100%";
iframe.style.border = "none";
iframe.src = url
win.document.body.appendChild(iframe)
}
</script>
</body>
</html>

<style>
body {
  background-image: url('https://wallpapercave.com/wp/wp5565660.jpg');
  background-repeat: no-repeat;
}
</style>

<img src="https://avatars.githubusercontent.com/u/160365698?v=4" alt="unfinished bingo card" onclick="openGame()" />
