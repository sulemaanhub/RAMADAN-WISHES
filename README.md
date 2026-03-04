# RAMADAN-WISHES
<!DOCTYPE html>
<html>
<head>
<title>Ramadan Mubarak</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body style="text-align:center; margin-top:100px; font-family:Arial;">

<h1>🌙 Ramadan Kareem 🌙</h1>

<button onclick="playSound()" style="padding:15px; font-size:18px;">
Play Audio 🔊
</button>

<br><br>

<audio id="myAudio" controls>
  <source src="ayo.mp3" type="audio/mpeg">
</audio>

<script>
function playSound() {
  var audio = document.getElementById("myAudio");
  audio.play().catch(function(error){
    alert("Audio blocked by browser. Please press play button below.");
  });
}
</script>

</body>
</html>

