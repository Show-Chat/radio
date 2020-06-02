
<html>
<head>
<title>Asculta RadioClick Romania</title>
<link href="radio.css" rel="stylesheet"> 
</head>
  <body>
<div class='player'>
   <img src='rcr.png'/>
   <div class='info'>
    <div class='name'>RadioClick</div>
    <div class='singer'>Romania</div>
  </div>
  <div class='btns'>
    <div class="iconfont play-pause icon-play"></div>
    <div class="iconfont next icon-next"></div>
  </div>
  <div class='progress'>
    
  </div>
</div>
<table class="center">
<audio id="stream" controls="" preload="none" autoplay="" style="width: 90%;">
<source src="http://live.radioclick.ro:8008/;" type="audio/mpeg">
</audio>
<script type="text/javascript">
var audio = document.getElementById('stream');
audio.volume = 0.5;
</script>
</table
  </div>
  
  <script src="radio.js"></script>
</body>
</html>
