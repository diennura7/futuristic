<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<title>Journey</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="css/main.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<style>
body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}

p{
	font-size:16px;
	padding-top:30px;
	padding-left:100px;
	padding-right:100px;
}

h3{
	font-size:10px;
}

.hero-image {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(img/img1.jpg);
  height: 50%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.hero-text {
	text-align: left;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	color: #fff;
}

.hero-text button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 10px 25px;
  color: black;
  background-color: #ddd;
  text-align: center;
  cursor: pointer;
}

.hero-text button:hover {
  background-color: #555;
  color: white;
}
<!-- -->
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

li {
    float: left;
}

li:last-child {
    border-right: none;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}
* {
    box-sizing: border-box;
}

/* Create three equal columns that floats next to each other */
.column {
    float: left;
    width: 33.33%;
    padding: 10px;
    height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

input[type=text] {
    width: 100%;
    border: none;
    border-bottom: 2px solid white;
	color:#000;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
    .column {
        width: 100%;
    }
}
</style>
</head>

<body>
<div class="hero-image">
<ul>
  <li><a class="active" href="#home"><span class="glyphicon glyphicon-send"></span>Journey</a></li>
  <li style="float:right"><a href="#about">Say Hello</a></li>
  <li style="float:right"><a href="#about">Latest News</a></li>
  <li style="float:right"><a href="#about">Our Work</a></li>
  <li style="float:right"><a href="#about">About Us</a></li>
  <li style="float:right"><a href="#about">Home</a></li>
</ul>
  <div class="hero-text">
    <h1><strong></strong>PLAN THE JOURNEY AHEAD</h1><br />
    <button style="background-color:#0033FF">View Project</button>
  </div>
</div>

<div class="w3-container">
	  <div class="w3-container w3-padding-64">
        <h1 class="w3-center"><strong>MAKE THIS HAPPEN</strong></h1>  
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent dolor sem, ultrices at feugiat sit amet, rhoncus a augue. Sed dapibus, neque sit amet sagittis dapibus, tortor tellus suscipit tortor, et consectetur ante ex et tortor. Suspendisse accumsan efficitur laoreet. Donec et velit cursus, pulvinar massa quis, auctor enim. Vestibulum blandit sed lectus non interdum. Fusce eu sodales tortor, eget posuere enim. Fusce vehicula nunc libero. </p>

<p>Praesent quis enim maximus, finibus turpis ut, tincidunt eros. Nulla feugiat accumsan varius. Mauris in massa ex. Donec accumsan molestie mattis. Morbi eget magna suscipit, maximus leo vel, pulvinar mauris. Proin ipsum turpis, pellentesque in ipsum id, tempus scelerisque metus. Curabitur volutpat elementum magna, vitae molestie ex lobortis vel. Vestibulum at turpis vel lectus auctor tempor. Donec lacinia interdum luctus. Mauris suscipit, arcu cursus dignissim porttitor, leo mauris tincidunt sapien, eu viverra velit dolor non diam. Maecenas semper ullamcorper elementum. Cras molestie ipsum sit amet purus sagittis, a ullamcorper orci molestie. Suspendisse eros tellus, tincidunt vel feugiat nec, consectetur at quam. Aliquam in viverra massa. Phasellus lacinia, diam vitae euismod egestas, turpis nisi sollicitudin lacus, sit amet gravida purus justo a nisi. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae</p>
	   </div>
</div>

<div class="container">
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <div class="w3-center">
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>
    

    <!-- Wrapper for slides -->
    <div class="carousel-inner">
      <div class="item active">
        <img src="img/1.jpg" alt="Image1" style="width:100%;">
      </div>

      <div class="item">
        <img src="img/2.jpg" alt="Image2" style="width:100%;">
      </div>
    
      <div class="item">
        <img src="img/3.jpg" alt="Image3" style="width:100%;">
      </div>
    </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div> <br /><br />

<div class="w3-container bg-primary w3-padding-64">
	  <p><i class="fa fa-twitter" style="font-size:32px;color:white"></i></p>
      <p>Yes. It's very true. We're going back to using MacPoint as of today. Don't try and stop us!</p>
 	  <p><button style="background-color: #000">Follow Us</button><p>
</div>

<div class="w3-row-padding">
    <div class="w3-third w3-margin-bottom w3-padding-64">
      <div class="w3-card-4">
        <img src="img/4.jpg" alt="Img" style="width:100%">
        <div class="w3-container">
          <p align="center">29th October 2017</p>
          <p align="center"><strong>We went on a lovely little trip down the river this summer</strong></p>
          <p align="center">Always be creating something amazing in everything you do and don't forget that there is always a way to achieve certain...</p>
         </div>
      </div>
    </div>

    <div class="w3-third w3-margin-bottom w3-padding-64">
      <div class="w3-card-4">
        <img src="img/4.jpg" alt="Img" style="width:100%">
        <div class="w3-container">
          <p align="center">21st October 2017</p>
          <p align="center"><strong>How our recent team get-together went south quite quickly</strong></p>
          <p align="center">Always be creating something amazing in everything you do and don't forget that there is always a way to achieve certain...</p>
        </div>
      </div>
    </div>

    <div class="w3-third w3-margin-bottom w3-padding-64">
      <div class="w3-card-4">
        <img src="img/4.jpg" alt="Img" style="width:100%">
        <div class="w3-container">
          <p>18th September 2017</p>
          <p align="center"><strong>365 Ways you can be a better designer in 1331 easy steps</strong></p>
          <p align="center">Always be creating something amazing in everything you do and don't forget that there is always a way to achieve certain...</p>
        </div>
      </div>
    </div>
  </div>
</div>

<footer class="w3-container w3-padding-64 w3-black">
<div class="row">
  <div class="column" style="background-color:black;">
    <p><strong> <span class="glyphicon glyphicon-send"></span> Journey </strong></p>
    <p align="justify" style="font-size:10px;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent dolor sem, ultrices at feugiat sit amet, rhoncus a augue. Sed dapibus, neque sit amet sagittis dapibus, tortor tellus suscipit tortor, et consectetur ante ex et tortor. Suspendisse accumsan efficitur laoreet.</p>
    <p style="font-size:12px;">Copyright <span class="glyphicon glyphicon-copyright-mark"></span> 2018 The Company. All Right reserved</p>
  </div>
  <div class="column" style="background-color:black;">
    <p><strong>NAVIGATE</strong></p> <br />
    <h3>About</h3>
    <h3>Blog</h3>
    <h3>Term of use</h3>
    <h3>FAQ</h3>
  </div>
  <div class="column" style="background-color:black;">
    <p><strong>FOLLOW US</strong></p> <br />
    <h3>Facebook</h3>
    <h3>Twitter</h3>
    <h3>Instagram</h3>
    <h3>Youtube</h3>
    <form>
	  <label for="mail"></label>
  	  <input type="text" id="mail" name="mail" placeholder="Enter your email adress" span class="glyphicon glyphicon-arrow-right">
	</form>
  </div>
</div>

</footer>


</body>
</html>
