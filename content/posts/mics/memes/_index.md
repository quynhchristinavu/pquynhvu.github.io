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

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

.row {
  display: flex;
}

/* Create three equal columns that sits next to each other */
.column {
  flex: 33.33%;
  padding: 5px;
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>Academic</p>

<div class="row">
  <div class="column">
    <img src="meme1.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="meme2.jpg" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="meme3.jpg" alt="Mountains" style="width:100%">
  </div>
</div>

</body>

<body>
<p> <em> Last updated </em> </p>
<p id="myId"></p> 
<script> 
var date = new Date(); 
var p = document.getElementById("myId"); 
p.innerHTML = date; 
</script> 
</body>