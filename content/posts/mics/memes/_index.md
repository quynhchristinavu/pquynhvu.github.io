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
</div>
<div class="image123">
    <div style="float:left;margin-right:5px;">
        <img src="/meme1.jpg" height="200" width="200"  />
        <p style="text-align:center;">This is image 1</p>
    </div>
    <div style="float:left;margin-right:5px;">
        <img class="middle-img" src="./meme2.jpg" height="200" width="200" />
        <p style="text-align:center;">This is image 2</p>
    </div>
    <div style="float:left;margin-right:5px;">
        <img src="./meme3.jpg" height="200" width="200" />
        <p style="text-align:center;">This is image 3</p>
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