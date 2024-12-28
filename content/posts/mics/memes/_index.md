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
    <style>
        .column {
            float: left;
            width: 30%;

        }

        img {
            width: 80%
        }
    </style>
</head>

<body>
    <div class="column">
        <img src="meme1.jpg">
    </div>
    <div class="column">
        <img src="meme2.jpg">
    </div>
    <div class="column">
        <img src="meme3.jpg">
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