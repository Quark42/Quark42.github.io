# Hello there!
I'm Quark a developer.



[![wiggly wobbly](https://avatars.githubusercontent.com/u/160365698?v=4)](https://github.com/Quark42)
<html>
<head>
</head>
<body>
<button onclick="openGame()">Open Gam</button>
<script>
function openGame() {
var win = window.open()
var url = "https://example.com"
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
