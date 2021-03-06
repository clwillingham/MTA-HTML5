<a name="top"></a>
# Practical HTML, CSS, and JS Exercises

#### Use these exercises to challenge and practice what you've learned in your lessons.  These may contain features you'd like to implement into your own portfolio.  It is recommended to attempt these using Codepen.io or c9.io before implementing into your own designs.



## Table of Contents
### [Big Red Button](#RedButton)
### [Vote for Pedro](#Pedro)
### [My Resume](#resume)
### [Landing Page for XYZ Co.](#landing)
### [My Hex Colors](#hex)
### [Navigation](#nav)
### [Hamburger Nav](#hnav)
### [Modal Pop Up](#modal)


***
<a name="RedButton"></a>
# Big Red Button 

## HTML
```HTML5
<button onclick="message()">Don't</button>
```

## CSS
```HTML5
button {
  height: 200px;
  width: 200px;
  border-radius: 200px;
  background: red;
  color: white;
  font-family: Impact;
  font-size: 40pt;
  text-transform: uppercase;
  }

```

## JS
```JavaScript
function message() {
  alert('Oh No!');
  }
```
[Back to Top](#top)
***
<a name="Pedro"></a>
# Vote for Pedro 

## HTML
```HTML5
<button onclick="clickMe()">Vote</button>
<p>Votes: <a id="clicks">0</div></p>
```

## CSS
```HTML5
button {
  height: 200px;
  width: 200px;
  border-radius: 200px;
  background: red;
  color: white;
  font-family: Impact;
  font-size: 40pt;
  text-transform: uppercase;
  }

button:hover {
  background: blue;
  transition: .5s;
}
```


## JS
```JavaScript
  var clicks=0;
  function clickMe(){
    clicks += 1;
    document.getElementById("clicks").innerHTML = clicks;
  }
```
[Back to Top](#top)
***
 <a name="resume"></a>
# My Resume

## HTML
```HTML5
<div class="intro">
	<h1>My Name</h1>
	<h3><a href="mailto:myemail@domain.com">MyEmail@domain.com</a></h3>
	<img src="http://www.rd.com/wp-content/uploads/sites/2/2016/02/06-train-cat-shake-hands.jpg" />
</div>

<h2>About</h2>
<p>Describe who you are and what you are looking for in a workplace.</p>

<h2>Education</h2>
<h3>West University High School</h3>
<h3>Graduated May 2017</h3>


<h2>Skills and Abilities</h2>
<ul>
<li>Certification in Microsoft Office PowerPoint 2013</li>
<li>Certified Microsoft Technology Associate, Software Development in C#</li>
<li>Customer Service Oriented</li>
</ul>
```

## CSS
```HTML5
/* Importing Google.com Font called Exo */
@import url('https://fonts.googleapis.com/css?family=Exo');

body {
	font-family: Arial;
	margin: 0 200px;
}

.intro {
	text-align: center;}

img {
	display: inline-block; 
	margin: auto;
	vertical-align: middle;
	height: 200px;
	width: 300px;
	border-radius: 160px;
}

h1 {
	text-align: center;
	font-family: 'Exo', sans-serif;
}

h2 {
	margin-top: 50px; /* Adding a little space between previous section's content and heading*/
	font-family: 'Exo', sans-serif;
	color: #ffffff;
	background: #1693A5;
	padding: 8px;
	width: 250px;
}

h3 {
	text-align: center;
	line-height: .8em;
}

/* Changing link color and remove underline */
a:link, a:visited, a:active {
color: #1693A5;
text-decoration: none;}

/* Link Hover color and H2 Hover - timed transition to fade color in*/
a:hover, h2:hover {color: #000000; 
	transition: .7s;}

```
[Back to Top](#top)
***
<a name="landing"></a>
# Landing Page for XYZ Co

## HTML
```HTML5
<div class="box">
	<h3>Our website is currently down for maintenance.  Fill out the form below to be notified when we're back online!</h3>
	<img src="http://uploads.webflow.com/58a6d3ec4844a92b609ec1f3/58b84fbfd8178b1159d14b97_xyz.png">
	
	<form>
		<input type="text" name="email" placeholder="Enter Your Email Address to Subscribe!">
		<br/>
		<input type="submit" name="join" value="Join our Mailing List!">
	</form>

</div>

```

## CSS
```HTML5
body {
	margin: 0 auto;
	padding: 0;
	background: #900C3F;
	color: #581845;
	font-family: Century Gothic;
	background: url(http://cdn.mysitemyway.com/etc-mysitemyway/backgrounds/legacy-previews/backgrounds/watercolor-grunge/watercolor-grunge-000038-coral-salmon.jpg) fixed;
	background-size: contain;
}

.box {
	margin: 25px auto;
	padding: 10px;
	height: 400px;
	width: 400px;
	background: rgba(255,195,166,.9);
	border-radius: 10px;
	border: 10px solid #C70039;
	text-align: center;
	opacity: .9;
}

h3 {
	color: #FF5733;
}

input[type=submit] {
	background: #FF5733;
	border: 5px solid #C70039;
	font-family: Century Gothic;
	text-transform: uppercase;
	font-weight: 900;
	font-size: 14pt;
}

input[type=text] {
	width: 90%;
	padding: 2px;
	text-align: center;
	color: #C70039;
	font-size: 14pt;
	font-weight: 500;
	border: 1px solid #C70039;
	margin: 0 0 15px 0;
}

img {
	height: 160px;
	width: auto;
	margin: 0 0 25px 0;
}
```

[Back to Top](#top)
***
<a name="hex"></a>
# My Hex Colors

## HTML
```HTML5
<h1>My Fav Hex Colors</h1>

<table>
	<th>My Hex Color Chart</th>
	<tr class="one"><td>Black</td></tr>
	<tr class="two"><td>Lilac</td></tr>
	<tr class="three"><td>Lavendar</td></tr>
	<tr class="four"><td>Lemonade</td></tr>	
	<tr class="five"><td>Hot Pink</td></tr>	
	<tr class="six"><td>Stone</td></tr>	
	<tr class="seven"><td>Earth</td></tr>
	<tr class="eight"><td>Ocean</td></tr>
	<tr class="nine"><td>Fire</td></tr>
	<tr class="ten"><td>Tomato</td></tr>
	<tr class="eleven"><td>Coral</td></tr>
	<tr class="twelve"><td>Sky</td></tr>
</table>
```

## CSS
```HTML5
body {
	font-family: Calibri;
	text-align: center;
	color:  #000;
	
}
tr {
	height 10px;
}

.one {
	background: #000;
	color: #fff;
}

.two {
	background: #a5a;
}

.three {
	background: #55a;
}

.four {
	background: #ffa;
}

.five {
	background: #ea5bac;
}

.six{
	background: #a6b7c8;
}

.seven {
	background: #99aa99;
}

.eight {
	background: #58aebc;
}

.nine {
	background: #ff3322;
}

.ten {
	background: #ff6347;
}

.eleven {
	background: #FF7F50;
}

.twelve {
	background: #2995e1;
}
```
[Back to Top](#top)
***

<a name="nav"></a>
# Navigation Bar

## HTML
```HTML5
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Register</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

## CSS
```HTML5
nav li {
  display: inline;
  background: #5a5;
  color: #fff;
  padding: 10px;
  font-family: Century Gothic;
  font-weight: 600;
  margin: 0 10px 0 0;
}

nav {
  position: fixed;
  margin: 0;
  padding: 10px 0;
  background: #eee;
  height: 55px;
  width: 98%;
}

ul li:hover {
  background: #5c5;
  transition: .5s;
  border: 10px solid #5a5;
  padding: 2px;
  cursor: crosshair;
}

a:link, a:visited, a:active, a:hover {
  color: #fff;
  text-decoration: none;
}
```

[Back to Top](#top)


***
<a name="hnav"></a>
# Hamburger Navigation 

## HTML
```HTML5
<div class="navcontainer">
	 <button id="navbtn"> &equiv; </button>

<nav id="navmenu">
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Register</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
</div>
```

## CSS
```HTML5
.navcontainer {
	background: #efe;
	height: 50%;
}

#navmenu {
	display: none;
	margin: 0;
	padding: 0;
}

.active {
	display: block !important;
	margin: 0;
	padding: 0;
}

ul li {
 	background: #5c5;
  	font-family: Georgia;
	font-size: 20pt;
	width: 115px;
	margin: 5px 0;
  	padding: 5px;
	list-style: none;
	border-right: 15px solid #5a5;
}

ul li:hover {
	border-right: 15px solid #5aa;
	transition: 1s;
	padding-left: 20px;
}

a:link, a:visited, a:active, a:hover {
  	cursor: crosshair;
	color: #fff;
  	text-decoration: none;
}

#navbtn {
	background: #5a5;
	color: #fff;
	font-size: 30pt;
	border:0;
	height: 50px;
	width: 50px;
}

#navbtn:hover {
	color: #fff;
	background: #5aa;
	transition: .5s;
}
```


## JS
Make sure you use the JQuery Library (Settings - JavaScript - JQuery)
https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js

```JavaScript
$("#navbtn").click(function(){
    $("#navmenu").toggleClass("active");
});
```
[Back to Top](#top)
***

<a name="modal"></a>
# Modal Pop Up

## HTML
```HTML5
<button id="register">Register here!</button>
	
	
	<div id="registerMod" class="modal">
	<div class="registerModContent">
		<span class="close"><p> &times; </p></span>
		<p>Thank you for your interest!</p>
		<input type="email" name="YourEmail" placeholder="Your Email"/>
		<button>Submit</button>
	</div>
	
	
	</div>
```

## CSS
```HTML5
.modal {
	display: none;
	margin: 0 auto;
	width: 100%;
	height: 100%;
	position: absolute;
	top: 0;
	right: 0;
	overflow: auto;
	background: rgba(100,100,100,.5);
	font-family: Georgia;
	text-align: center;
	font-size: 14pt;
}

.registerModContent {
	background: #eee;
	margin: 20px auto;
	padding: 0px 20px 50px 20px;
	border: 2px solid #888;
	max-width: 50%;
}


.close p {
	color: orange;
	padding: 0 10px 0 0;
	font-size: 40pt;
	font-weight: bold;
	text-align: right;
	line-height: 0px;
}

.close p:hover, .close p:focus {
	color: red;
	text-decoration: none;
}
```


## JS

```JavaScript
var modal = document.getElementById("registerMod");

var btn = document.getElementById("register");

var span = document.getElementsByClassName("close")[0];

btn.onclick = function() {
	modal.style.display = "block";
}

span.onclick = function () {
	modal.style.display = "none";
}

window.onclick = function(e) {
	if (e.target == modal) {
		modal.style.display = "none";
	}
}
```
[Back to Top](#top)
***

