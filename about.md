<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Home Page</title>
<style>
	@import ="css/style.css"	
</style>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
<style type="text/css">
.carousel{
    background: #2f4357;
    margin-top: 20px;
}
.carousel .item img{
    margin: 0 auto;
}
.bs-example{
	margin: 20px;
}
</style>
</head>
<body>
<div class="bs-example">
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
            <li data-target="#myCarousel" data-slide-to="1"></li>
            <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>   
        <div class="carousel-inner">
            <div class="item active">
                <img src="img/profile/profile.jpg" alt="Profile Image">
            </div>
            <div class="item">
                <img src="img/profile/dcfe.jpg" alt="Image of Killian">
            </div>
            <div class="item">
                <img src="img/profile/town.jpg" alt="Photo of Killian">
            </div>
		</div>
        <a class="carousel-control left" href="#myCarousel" data-slide="prev">
            <span class="glyphicon glyphicon-chevron-left"></span>
        </a>
        <a class="carousel-control right" href="#myCarousel" data-slide="next">
            <span class="glyphicon glyphicon-chevron-right"></span>
        </a>
    </div>
</div>                               		
    <div class="container">
    <div>
                <ul class="nav navbar-nav">
                    <li>
                        <a href="index.html">Home</a>
                    </li>
                    <li>
                        <a href="about.html">About</a>
                    </li>
                    <li>
                        <a href="photo.html">Photography</a>
                    </li>
                    <li>
                        <a href="design.html">Design</a>
                    </li>
                    <li>
                        <a href="media.html">Media</a>
                    </li>
                    <li>
                        <a href="contact.html">Contact</a>
                    </li>
                </ul>
            </div><hr>

    <div class="container">

        <div class="row">
            <div class="col-lg-12">
                <h1>
                    <small>About Killian Kelly</small>
                </h1>
            </div>
        </div>

        <div class="row">
            <div class="col-md-3 portfolio-item">
                	<div id="about">

					<p>This is the portfolio page of Killian Kelly,
					a Creative Digital Media student in the Institute of Technology, Blanchardstown.
					I've always had an interest in photography and when I found the Creative Digital Media course I had to jump at the chance to do it.
					I also enjoy working in design and media and
					I've also an interest in developing websites.</p>
					</div>
            </div>
            <div class="col-md-3 portfolio-item">
					<p>My work revolves around photography, website design and videography.
						I have studied many modules while doing the Creative Digital Media course in the Institute of Technology, Blanchardstown</p>
            </div>
            <div class="col-md-3 portfolio-item">
                		<p>like Digital Photography, Design Process and Practice, Website Development and Digital Media.
						You can view some of my work by clicking on the links below;
						<a href="photo.html"> Photography Work</a>
						<a href="design.html"> Design Work</a>
						<a href="media.html"> Media Work</a></p><hr>
            </div>
        </div>

<footer>
        <p>Copyright &copy; Killian Kelly 2017</p>
</footer>
	</div>
   
    <!-- jQuery -->
    <script src="file:///C|/Users/Vada/Documents/Bootstrap/js/jquery.js"></script>

    <!-- Bootstrap Core JavaScript -->
    <script src="file:///C|/Users/Vada/Documents/Bootstrap/js/bootstrap.min.js"></script>
	</div>
</body>

</html>
