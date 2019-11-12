---
title: 
feature_text: | 
feature_image: "/header2.png" 
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
button {
     width: 50%;
     height: 50%;
}
	
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
  width: 40%;
}

.right {
  width: 60%;
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


<div class="row" align="left">
  <div class="column left" align = "center" style="background-color:#ffffff;">
     <img src="/headshot.jpg" style="width:100%">
     <p style="text-align:center">Jenni Putz <br />
   <font size="-1"> Doctoral Student <br /> Department of Economics <br /> University of Oregon</font></p>
	  
{% include button.html text="Github" icon="github" link="https://github.com/jenni-putz" color="#8596B1" %} {% include button.html text="Twitter" icon="twitter" link="https://twitter.com/pootzie_xoxo" color="#8596B1" %} {% include button.html text="Email" icon="email" link="mailto:jputz@uoregon.edu" color="#8596B1" %} 
  </div>
  
  <div class="column right" style="background-color:#ffffff;">
  <h2> Teaching </h2>
  <h3>As an independent instructor: </h3>
    <ul>
    <li> EC 311: Intermediate Microeconomics </li>
    Summer 2019 <a href="/EC311Syllabus.pdf">Syllabus</a>
    <li> EC 333: Resource and Environmental Economic Issues </li>
    Spring 2020 (Scheduled)
    </ul>
    <h3> As a lab instructor: </h3>  
    <ul>
    <li> EC 320: Introduction to Econometrics </li> 
    Fall 2018, Winter 2019
    <li> EC 421: Introduction to Econometrics </li> 
    Spring 2019, Fall 2019
    <li> EC 425/525: Econometrics (First year PhD course) </li> 
    Spring 2019
    </ul>
  </div>
</div>

</body>
</html>
 
