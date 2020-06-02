
<html>
<head>
<title>Asculta RadioClick Romania</title>

  <script type="text/javascript">
  function audioControl() {
    var playdiv = document.getElementById('playdiv');
    var pausediv = document.getElementById('pausediv');
    var myAudio = document.getElementById('myAudio');
    if (myAudio.paused) {
    myAudio.play();
    pausediv.style.display = 'block';
    playdiv.style.display = 'none';
    } else {
    myAudio.pause();
    pausediv.style.display = 'none';
    playdiv.style.display = 'block';
    }
  }
</script>
</head>
  <body>
<table class="center">
  
  <audio id="myAudio" autoplay preload="metadata">
   <source src="http://live.radioclick.ro:8008/;"></source>
   Unfortunately your browser doesn't support html5 audio streaming, please update your browser.
</audio>

<button id="control" class="control" onclick="audioControl()">
   <div id="playdiv" style="display:none">
      <img src="play.png" width="100" height="100" alt="play"/>
   </div>
   <div id="pausediv" style="display:block">
      <img src="pause.png" width="100" height="100" alt="pause"/>
   </div>
</button>
  
</table>
</body>
</html>
