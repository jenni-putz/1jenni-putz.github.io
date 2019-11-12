---
title: 
feature_text: | 
feature_image: "/header.png" 

---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
img {
  border-radius: 50%;
}
</style>
   
<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 0px;
  height: 700px; 
}

.left {
  width: 100px;
}

.right {
  width: 500px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>


<div class="row" align="left" style="width: 1000px">
  <div class="column left" align = "center" style="background-color:#aaa;">
     <img src="/headshot.jpg" style="width:200px">
     <p style="text-align:center">Jenni Putz <br />
   <font size="-1"> Doctoral Student <br />
    Department of Economics <br />
     University of Oregon</font></p>
  </div>
  <div class="column right" style="background-color:#bbb;">
    <p>test3 I am a third year PhD student at the University of Oregon. My research interests are in education, environmental, and behavioral economics. <br />

{% include button.html text="Github" icon="github" link="https://github.com/jenni-putz" color="#8596B1" %} {% include button.html text="Twitter" icon="twitter" link="https://twitter.com/pootzie_xoxo" color="#8596B1" %} {% include button.html text="Email" icon="email" link="mailto:jputz@uoregon.edu" color="#8596B1" %} </p>
  </div>
</div>

</body>
</html>



