# Hello there!
I'm Quark a developer that creates

<html>
<head>
</head>
<body>
<button onclick="openGame()">Open Game</button>
<script>
function openGame() {
var win = window.open()
var url = "https://youtube.com"
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
<p style="background-image: url('https://wallpapercave.com/wp/wp5565660.jpg');">
<img src="https://avatars.githubusercontent.com/u/160365698?v=4" alt="unfinished bingo card" onclick="openGame()" />
