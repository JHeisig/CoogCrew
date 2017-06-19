<html>
<head>
<title> Bootstrap </title>
<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
<title> Bootstrap </title>
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
<!-- Optional theme -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: Red;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
	font-size: 10;
}

li a:hover {
    background-color: maroon;
	color:white;
}
.active {
    background-color: Firebrick;
}

/* Add a gray right border to all list items, except the last item (last-child) */
li {
    border-right: 1px solid #bbb;
}

li:last-child {
    border-right: none;
}

	
	
	.ccnavbar{text-align:center}
.ccnavbar ul{
	display:inline-block;
	text-align:left;
	margin: 0; 
	padding: 0;
	
}
		
	/* Set black background color, red text and some padding */
    footer {
      background-color:Black;
      color: red;
      padding: 15px;
    }
    carousel-inner img {
      width: 100%; /* Set width to 100% */
      margin: auto;
      min-height:200px;
  }

  /* Hide the carousel text when the screen is less than 600 pixels wide */
  @media (max-width: 600px) {
    .carousel-caption {
      display: none; 
    }
  }

    /* Remove the navbar's default margin-bottom and rounded borders */ 
    .navbar {
      margin-bottom: 0;
      border-radius: 0;
    }
        
    /* Set black background color, red text and some padding */
    footer {
      background-color:Black;
      color: red;
      padding: 15px;
    }    
 </style>


</head>

<header>
<body>
<div>
<h1> <!--Header on the page -->
<center> <!--link below is image of the header -->
<img src="https://scontent-ort2-1.xx.fbcdn.net/v/t31.0-8/18192353_10209365351910032_4339901019942534278_o.jpg?oh=4b885beeda2e6b7752de0e0305eede66&oe=59E36C0A" alt="Coog Crew Logo"  width="100%" height="210s" style="float left">
</center>
</h1>
</div>


<div class="ccnavbar">
<h3>
<ul>
  <li><a class="active" href="#home">Home</a></li>
		<li><a href="#">About Us</a></li>
        <li><a href="#">Join Us</a></li>
		<li><a href="#">Members</a></li>
		<li><a href="#">Calender</a></li>
		<li><a href="#">Sponsors</a></li>
</ul>
</h3>
</div>




<div class="col-sm-7 text-left"> 
      <h1>Announcements</h1>
      <p>All Coog Crew announcements will go here<br> All announcements</p>
      <hr>
      <h3>Anything else we want to write</h3>
      <p>Can go under a secondary header</p>
    </div>


<div class="container">
<div class="row">
  <div class="col-sm-8">
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
      </ol>

      <!-- Wrapper for slides -->
      <div class="carousel-inner" role="listbox">
        <div class="item active">
          <img src="https://placehold.it/800x400?text=IMAGE" alt="Image">
          <div class="carousel-caption">
            <h3>Houston</h3>
            <p>Money Money.</p>
          </div>      
        </div>

        <div class="item">
          <img src="https://placehold.it/800x400?text=Another Image Maybe" alt="Image">
          <div class="carousel-caption">
            <h3>More Sell $</h3>
            <p>Lorem ipsum...</p>
          </div>      
        </div>
      </div>

      <!-- Left and right controls -->
      <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</div>
</div>


<aside>
<div align="right">
<a class="twitter-timeline" data-lang="en" data-width="300" data-height="300" href="https://twitter.com/UHCougars">Tweets by UHCougars</a> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>
</aside>




<footer>
Follow us
</footer>

