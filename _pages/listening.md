---
layout: page
title: "Listening List"
permalink: /listening/
---

# Listening List 

<div style = "color: ##bb0091;">
  Have you heard these songs? Click on the stars to listen.
</div>

<div class ="indent" style = "color: #1d27fa;">
favourite daughter - lorde
  <a href="/assets/favourite-daughter.mp3" onclick="playOnly('favd'); return false;">
          ✩₊˚.⋆☾⋆⁺₊✧✩‧₊˚  
  </a>
  <audio id="favd" src="/assets/favourite-daughter.mp3"></audio>
  <p><a href="/2025/07/03/favourite-daughter.html">my post about this song</a></p>
</div>
<div class = "indent" style = "color:#719f7e;">
i can and i will - searows
 <a href="/assets/icaniwill.mp3" onclick="playOnly('icaiw'); return false;">
          ✩₊˚.⋆☾⋆⁺₊✧✩‧₊˚  
  </a>
  <audio id="icaiw" src="/assets/icaniwill.mp3"></audio>
</div>
<div class = "indent" style = "color:#58b6c3;">
blade bird - okloug
  <a href="/assets/bladebird.mp3" onclick="playOnly('bbird'); return false;">
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

  document.getElementById(id).play();
}
</script>


