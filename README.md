<!doctype html>

<html>

	echo "# ashortridge.github.io" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/ashortridge/ashortridge.github.io.git
	git push -u origin main

<html lang="en">
<head>
	<meta charset="utf-8">
	
	<title>My Final Webpage</title>
	
		<style type="text/css">
			
			/* http://meyerweb.com/eric/tools/css/reset/ 
	   v2.0 | 20110126
	   License: none (public domain)
	*/

		html, body, div, span, applet, object, iframe,
		h1, h2, h3, h4, h5, h6, p, blockquote, pre,
		a, abbr, acronym, address, big, cite, code,
		del, dfn, em, img, ins, kbd, q, s, samp,
		small, strike, strong, sub, sup, tt, var,
		b, u, i, center,
		dl, dt, dd, ol, ul, li,
		fieldset, form, label, legend,
		table, caption, tbody, tfoot, thead, tr, th, td,
		article, aside, canvas, details, embed, 
		figure, figcaption, footer, header, hgroup, 
		menu, nav, output, ruby, section, summary,
		time, mark, audio, video {
			margin: 0;
			padding: 0;
			border: 0;
			font-size: 100%;
			font: inherit;
			vertical-align: baseline;
		}
		/* HTML5 display-role reset for older browsers */
		article, aside, details, figcaption, figure, 
		footer, header, hgroup, menu, nav, section {
			display: block;
		}
		
		/*
			font-family: 'Cardo', serif;
			font-family: 'Josefin Sans', sans-serif;
			font-family: 'Josefin Slab', serif;
			*/

		body {
			line-height: 1;
			font-family: 'Cardo', serif;
		}
		
		article>p{
			line-height: 130%;
		}
		
		h1,h2, h3, h4, h5, h6{
			font-family: 'Josefin Sans', sans-serif;
			color: #ea3057;
			letter-spacing: .025em;
		}
		
		h1{
			font-size: 2em;
			font-weight: bold;
		}
		
		h2{
			font-size: 1.7em;
			font-weight: bold;
		}
		
		ol, ul {
			list-style: none;
		}
		blockquote, q {
			quotes: none;
		}
		blockquote:before, blockquote:after,
		q:before, q:after {
			content: '';
			content: none;
		}
		table {
			border-collapse: collapse;
			border-spacing: 0;
		}
		
			#wrapper{
				width: 80.56640625%;
				margin: 0 auto;
				background-color: #e5e5e5
			}
			
			nav{
				margin: 0 auto;
				background-color: #b1a7a5;
				padding: 1% 0;
			}
			
			nav ul{
				width: 85.57575757575758%;
				margin: 0 auto;
			}
			
			nav ul li{
				display: inline;
				margin-right: 2%;
			}

			.nav-item{
				display: inline-block;
				margin-left: 2%;
				background-color: white;
			}
			
			li.nav-item a:hover{
				color: white;
				background-color: #5b5553;
			}
			
			li.nav-item a:link{
				color: red;
			}
			
			body{
				background-color: #5b5553;
			}
			header{
				background-color: white;
				padding: 3%;
			}
			
			#feature{
				width: 81.32575757575758%;
				margin: 3% auto 4% auto;
				background-color: white;
				overflow: hidden;
				padding: 1.5% 2.25% 3.5% 2.25%;
			}
			
			.feature-img{
				float: left;
				width: 40%;
			}
			.feature-text{
				float: left;
				width: 58%;
				margin-left: 2%;
				font-family: 'Josefin Slab', serif;
				font-size: 1.55em;
				font-weight: bold;
				line-height: 115%;
				letter-spacing: .025em;
			}
			
			#main-content{
				width: 59.39393939393939%;
				float: left;
				margin: 2%;
			}
			
			.main-figure{
				width: 32.50478011472275%;
				margin-right: 9.56022944540669%;
				float: right;
			}
			
			#sidebar{
				width: 32.60606060606061%;
				float: left;
				margin: 2%;
			}	
			
			.side-figure{
				width: 88.0794701986755%;
				margin: 0 auto;
				padding: bottom: 2%;
			}
			
			figure img{
				max-width: 100%;
			}
			
			figure{
				background-color: silver;
			}
			footer{
				clear: left;
				padding: 2%;
			}
			
			footer p{
				margin: 0;
			}
			
			/*type styles*/
			#feature h2{
				margin-bottom: 2%;
			}
			
			p{
				margin: 2.5% 0;
			}
			
			figcaption{
				font-family: 'Josefin Slab', serif;
				margin: 3%;
			}
			
			#sidebar figcaption{
				margin-bottom: 6%;
			}
			
		</style>
		
		
		<!--[if lt IE 9]>
		<script src="
		https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.js"></script>
	<![endif]-->
	
</head>

<body>
	<div id="wrapper">
		<header>
			<h1>Traveling Soccer<h1>
		</header>
		
		<nav>
			<ul>
				<li class="nav-item"><a href="MultiColumn2.html">page 2</a></li>
				<li class="nav-item"><a href="MultiColumn3.html">page 3</a></li>
				<li class="nav-item"><a href="MultiColumn4.html">page 4</a></li>
				<li class="nav-item"><a href="MultiColumn5.html">page 5</a></li
			</ul>
		</nav>
		
		<div id="feature">
			<h2>About Soccer</h2>
			
			<img src="
			https://media.istockphoto.com/photos/soccer-ball-in-the-corner-of-football-field-picture-id1183054977?b=1&k=6&m=1183054977&s=170x170&h=B7Jp1Lfq3qNWrVGsB0oPxumbzPqqQ7HThv08xSGV7FQ=" class="feature-img"/> 
			
			<p class="feature-text">Soccer is a game played by two teams of eleven players with 
			a round ball that may not be touched with the hands or arms during play 
			except by the goalkeepers. The object of the game is to score goals by 
			kicking or heading the ball into the opponents' goal.
				</p>
		</div>
		
		<div id="main-content">
			<article>
				<h2>Equipment</h2>
				<figure class="main-figure">
					<img src="
					https://patch.com/img/cdn20/users/22973923/20201005/032733/styles/patch_image/public/pixabay-soccer-gear___05152727131.jpg" />
					<figcaption>
						<p>Soccer equipment</p>
					</figcaption>
				</figure>
				<p>
				In order to be elgiable to play in a soccer match you need to be 
				properly equipped. To be properly equipped you need to be wearing
				shin guards and socks to go over them, soccer cleats without any metal 
				on the bottom, a unifrom with a unique number that matches the rest of
				your team, a ball that is supplied by the home team. If you are a
				goalie you can wear gloves if you choose to.
				</p>
				<p>
				Most of your equipment can be found at a sporting store like Dick's
				Sporting Goods, Nike, Adidas, Under Armour, or any soccer store. Additional 
				iteams can be purchased through a website provided by your team or club.
				Through that link you may be able to purchase things like uniforms, a team bag, or a team ball.
				</p>
				<p>
				Additonal equipment can be purcahsed to help you improve on your speed,
				moves, or agility. You could purcahse a ladder to help work on quick speed 
				and change of direction, cones to help with dribbling and foot skills, or weights
				to help build your muscle that will then help to improving your speed. Those are
				just a few examples to help but many more are avaliabe for you to find online.
				</p>
			</article>

		</div>
		<div id="sidebar">
			<article>
				<h2>Formation</h2>
				<figure class="side-figure">
					<img src="
					https://media.istockphoto.com/photos/aerial-photo-of-soccer-field-picture-id155377221?k=20&m=155377221&s=612x612&w=0&h=LWxqSPgvJyzrHd_qKokRCufxFDeFzU1f3OIQ19nOVmg=" />
					<figcaption>
						<p>Soccer field</p>
					</figcaption>
				</figure>
				<p>
				Depending on your age will depend on how many players there will be 
				on the field per team and how many will be on a team. U10 and under will have 7 per team on a field at a time with a max of 12 players rostered.
				U11 and U12 will have 9 players per team on the field at a time and no more than 16 players on a team.
				U13 and up will have 11 players per team on a field at a time and no more than 22 players rostered.
				</p>
			</article>
		</div>
	<div>
		<footer>
			<p><small>Aleah Shortridge, Febuary 2024</small></p>
		</footer>
	</div><!--Close wrapper-->

</body>
</html>
