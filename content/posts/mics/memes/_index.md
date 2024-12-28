---
title: 
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 1

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""
---

<div class="row">
  <div class="column">
    <img src="meme1.jpg" alt="PhD life" style="width:100%">
  </div>
  <div class="column">
    <img src="meme2.jpg" alt="Green's Theorem" style="width:100%">
  </div>
  <div class="column">
    <img src="meme3.jpg" alt="et al" style="width:100%">
  </div>
</div>

<body>
<p> <em> Last updated </em> </p>
<p id="myId"></p> 
<script> 
var date = new Date(); 
var p = document.getElementById("myId"); 
p.innerHTML = date; 
</script> 
</body>