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
<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>HTML</title>
<style>
	
	.column {
	  flex: 30%;
	  padding: 5px;
	}
	img {
	  width: 100%;
	}
	.container {
	   display: flex;
	}

	
</style>
</head>  
<body>
    <h2>Welcome to the world of memes!</h2>
	<div class="container">
	   <div class="column">
	     <img src="meme1.jpg" height="300" width="250" alt="image1">
	   </div>
	   <div class="column">
	     <img src="meme2.jpg" height="300" width="250" alt="image1">
	   </div>
	   <div class="column">
	     <img src="meme5.jpg" height="300" width="250" alt="image1">
	   </div>
	</div>
	<div class="container">
	   <div class="column">
	     <img src="meme3.jpg" height="300" width="250" alt="image1">
	   </div>
	   <div class="column">
	     <img src="meme4.jpg" height="300" width="250" alt="image1">
	   </div>
	</div>
</body>
</html> 

<body>
<p> <em> Last updated </em> </p>
<p id="myId"></p> 
<script> 
var date = new Date(); 
var p = document.getElementById("myId"); 
p.innerHTML = date; 
</script> 
</body>