---
layout: page
title: "Listening List"
permalink: /listening/
---

# Listening List 
<div style = "color: ##b900bb;">
  🎶
</div>

<div style = "color: #00951d;">
  Have you heard these songs? Click on the stars to listen.
</div>

<div class ="indent" style = "color: #1d27fa;">
favourite daughter - lorde
  <a href="#" onclick="playOnly('favd'); return false;">
          ✩₊˚.⋆☾⋆⁺₊✧✩‧₊˚  
  </a>
  <audio id="favd" src="/assets/favourite-daughter.mp3"></audio>
</div>

<div class = "indent" style = "color:#719f7e;">
i can and i will - searows
 <a href="#" onclick="playOnly('icaiw'); return false;">
          ✩₊˚.⋆☾⋆⁺₊✧✩‧₊˚  
  </a>
  <audio id="icaiw" src="/assets/icaniwill.mp3"></audio>
</div>
<div class = "indent" style = "color:#58b6c3;">
blade bird - oklou
  <a href="#" onclick="playOnly('bbird'); return false;">
          ✩₊˚.⋆☾⋆⁺₊✧✩‧₊˚  
  </a>
  <audio id="bbird" src="/assets/bladebird.mp3"></audio>
</div>

<script>
function playOnly(id) {
  document.querySelectorAll('audio').forEach(function(audio) {
    audio.pause();
    audio.currentTime = 0;
  });

  g
  document.getElementById(id).play();
}
</script>


