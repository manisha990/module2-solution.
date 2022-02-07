# module2-solution.
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewpoint" content="width=device-width, initial-scale=1">
<title>Restaurant Menu</title>
</head>

<style>

/* all h2 elements */

.column {
flex: 33%;
height: 200 px;
padding: 10px;
border: 2px;
margin: 5px;
background-color: yellow;
text-align: right;
}
.container {
 display: flex;
}
#p1 {
color: white;
background-color: lightgreen;
clear: right;
}
#p2 {
color: red;
background-color: pink;
clear: right;
}
#p3 {
color: lightblue;
background-color: violet;
clear: right;
}
section {
clear: right;
}

</style>
<body style="background:lightgray;>
<div class="container">
<h1 style="color:blue; text-align:center;">Restaurant Menu</h1>
</div>

<div>
<p id="p1"></p>
<p id="p2"></p>
<p id="p3"></p>

<div class="container">
<div class="column">

<h2>Starters</h2>
<p id="p1"> Here you can see our various list of starters of any taste</p>
</div>
<div class="column">
<h2> Main</h2>
<p id="p2"> You can see our choice of different main dishes below</p>
</div>
<div class="column">
<h2> Desserts</h2>
<p id="p3"> Finish your experience with our beautiful desserts</p>
</div>
</div>

</body>
</html>
