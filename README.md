# my_first_site
HTML part

<!DOCTYPE html>
<html>
	<head>
		<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
		<title></title>
	</head>
	<body>
		<div id="header">
			<p id="name">Rezunyk Dmytro</p>
			<a href="mailto:charley.live@gmail.com"><p id="email">charley.live@gmail.com</p></a>
		</div>
		<div class="left"></div>
		<div class="right">
			<h4>Objective</h4>
			<p>To take a position as a software engineer.</p>
			<h4>Experience</h4>
			<p>Junior Developer</p>
			<ul>
				<li>Designed and implemented end-user features for Myself</li>
				<li>Аspiration to learn JavaScript and Ruby libraries</li>
			</ul>
			<h4>Skills</h4>
			<p>Languages: russian, ukranian, cobra :D, dota 2</p>
			<h4>Education</h4>
			<p>Poltava University of Economics and Trade</p>
		</div>
		<div id="footer">
			<p>Petra Yurchenka 19 Street, Poltava, Ukraine, 36007 | Tel: (050) 57-93-701</p>
		</div>
	</body>
</html>


CSS part


div {
	border-radius: 5px;
}

#header {
	z-index: 1;
	position: fixed;
	width: 97.5%;
	margin-top: -20px;
	height: 60px;
	background-color: #668284;
	margin-bottom: 10px;
}

#name {
	float:left;
	margin-left: 5px;
	padding-top: 5px;
	font-size: 16px;
	font-family: Verdana, sans-serif;
	color: #ffffff;
}

#email{
	float:right;
	margin-right: 5px;
	padding-top: 5px;
	font-size: 16px;
	font-family: Verdana, sans-serif;
	color: #ffffff;
}

h4 {
	margin-left: 5px;
	margin-bottom: 15px;
	font-family: Verdana, sans-serif;
}

.right p {
	margin-left: 5px;
	margin-right: 5px;
	margin-top: -10px;
	font-family: Garamond, serif;
	color: #000000;
}

li {
	list-style-type: square;
}

a:hover {
	font-weight: bold;
}

.left {
	position: relative;
	float: left;
	margin-top: 50px;
	width: 10%;
	height: 400px;
	background-color: #B9D7D9;
	margin-bottom: 10px;
}

.right {
	position: relative;
	float: right;
	margin-top: 50px;
	width: 88%;
	height: 400px;
	background-color: #F4EBC3;
	margin-bottom: 10px;
}

#footer {
	position: relative;
	height: 50px;
	background-color: #668284;
	clear: both;
	font-family: Verdana, sans-serif;
	font-size: 14px;
	text-align: center;
	color: #ffffff;
}

#footer p {
	position: relative;
	padding-top: 15px;
}
