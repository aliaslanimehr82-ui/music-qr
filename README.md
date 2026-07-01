<!DOCTYPE html>
<html lang="fa">
<head>
<meta charset="UTF-8">
<title>Music</title>
</head>
<body style="display:flex;justify-content:center;align-items:center;height:100vh;">
<audio id="music" controls autoplay>
  <source src="LINK_TO_MP3" type="audio/mpeg">
</audio>

<script>
window.onload = function () {
  document.getElementById("music").play().catch(() => {});
};
</script>
</body>
</html>
