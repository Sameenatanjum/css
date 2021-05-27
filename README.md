# css
css task
<head> 
<title>Essentials</title>
<meta charset="utf-8">
<LINK REL="stylesheet" type="text/css" href="style.css">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap" rel="stylesheet">
</head>
<ul>
					<li><a class="active" href= "#" >home</a></li>
					<li><a href ="sam3.html" >About us </a>  
	
					</li> <li> <a href="Products.html" >Products </a> </li>
					<li><a href="sam1.html"> login</a></li>
				</ul>
			
				<div class="content-zone">
					<div class="wrapper">
						<div id=home" class="banner">
							<div class="text">
								<h2>Home</h2>
							</div>
						</div>
						<div id="About" class="product-zone">
							<div class="text">
								<h2>login</h2>
							</div>
						</div>
						<div id="product" class="product-zone">
							<div class="text">
								<h2>product</h2>
							</div>
						</div>
						<div id="login" class="product-zone">
							<div class="text">
								<h2>login</h2>
							</div>
						</div></div></div></LINK>
                               *{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
body{
	font-family: josefin sans;
}
ul{
	
	color:black;
	width:248px;
	height: 100%;
	position:fixed;
	z-index:1;
	top: 0;
	left: 0;
	overflow-x: hidden;
	background-color:black;
	list-style-type: none;
}
li a{
	display:block;
	color:#fff;
	text-align:center;
	padding:50px 10px;
	text-decoration:none;
	font-size:20px;
	font:weight:600;
text-decoration:none;
}
li a:hover{
	background-color:#808080;

}
.active{
	background:#00997a;

}
.wrapper{
	width: 100%;

}
.banner{
	height: 100vh;
	width:100%;
	overflow:hidden;
	background-image: url(https://i.pinimg.com/originals/1d/fa/b3/1dfab39bda73132514a503a29d4302bd.jpg);
	background-size: cover;
	background-position: center center;

}
.about-zone,
.product-zone,
.contact-zone{
	height: 100vh;
}
.text h2{
	text-align: center;
	text-transform: uppercase;
	padding-top: 20%;
	font-size: 70px;
	margin:0;
	color:#fff;
	text-shadow:0 5px 10px #000;
}
.content-zone{
	margin-left;
}
