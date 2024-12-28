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
<body>
</div>
<div class="image123">
    <div style="float:left;margin-right:5px;">
        <img src="./meme1.jpg" height="250" width="300"  />
        <p style="text-align:center;"> </p>
    </div>
    <div style="float:left;margin-right:5px;">
        <img class="middle-img" src="./meme2.jpg" height="300" width="250" />
        <p style="text-align:center;"> </p>
    </div>
    <div style="float:left;margin-right:5px;">
        <img src="./meme3.jpg" height="300" width="250" />
        <p style="text-align:center;"> </p>
    </div>
    <div style="float:left;margin-right:5px;">
        <img src="./meme4.jpg" height="300" width="250" />
        <p style="text-align:center;"> </p>
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