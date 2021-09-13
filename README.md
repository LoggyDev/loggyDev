<!doctype html>
<html>
	<header>
		<!-- Name of the website -->
		<title>LoggyDev.com</title>
		
		<!-- Icon -->
		<link rel="apple-touch-icon-precomposed" sizes="57x57" href="apple-touch-icon-57x57.png" />
		<link rel="apple-touch-icon-precomposed" sizes="114x114" href="apple-touch-icon-114x114.png" />
		<link rel="apple-touch-icon-precomposed" sizes="72x72" href="apple-touch-icon-72x72.png" />
		<link rel="apple-touch-icon-precomposed" sizes="144x144" href="apple-touch-icon-144x144.png" />
		<link rel="apple-touch-icon-precomposed" sizes="60x60" href="apple-touch-icon-60x60.png" />
		<link rel="apple-touch-icon-precomposed" sizes="120x120" href="apple-touch-icon-120x120.png" />
		<link rel="apple-touch-icon-precomposed" sizes="76x76" href="apple-touch-icon-76x76.png" />
		<link rel="apple-touch-icon-precomposed" sizes="152x152" href="apple-touch-icon-152x152.png" />
		<link rel="icon" type="image/png" href="favicon-196x196.png" sizes="196x196" />
		<link rel="icon" type="image/png" href="favicon-96x96.png" sizes="96x96" />
		<link rel="icon" type="image/png" href="favicon-32x32.png" sizes="32x32" />
		<link rel="icon" type="image/png" href="favicon-16x16.png" sizes="16x16" />
		<link rel="icon" type="image/png" href="favicon-128.png" sizes="128x128" />
		<meta name="application-name" content="&nbsp;"/>
		<meta name="msapplication-TileColor" content="#FFFFFF" />
		<meta name="msapplication-TileImage" content="mstile-144x144.png" />
		<meta name="msapplication-square70x70logo" content="mstile-70x70.png" />
		<meta name="msapplication-square150x150logo" content="mstile-150x150.png" />
		<meta name="msapplication-wide310x150logo" content="mstile-310x150.png" />
		<meta name="msapplication-square310x310logo" content="mstile-310x310.png" />

		<!-- To style the site -->
		<style>
			.video {
				display: inline;
				border-radius: 10px 10px;
			    position: absolute;
			    top: 0; 
			    right: 0;
			    bottom: 0; 
			    left: 0;
			    margin: auto;
			    animation-duration: 1.1s;
  				animation-name: slidein;
			}

			.TitleBar {
				animation-duration: 0.5s;
  				animation-name: slidein;
				margin: -8px;
				padding: 0;
				overflow: hidden;
				background-color: #2D2D2D;
			}

			.TitleText {
				animation-duration: 1s;
  				animation-name: slidein;
				text-decoration: none;
				margin: 8px;
				padding: 4px 8px;
				color: white;
				display: inline;
				border-radius: 4px 8px;
				font-family: Arial;
				background-color: #202020; 
				transition: background-color 0.3s ease
			}

			.TitleText:hover {
				background-color: #777777;
				transition: background-color 0.3s ease
			}

			.title {
				display: inline;
				overflow: hidden;
				color: white;
				position: relative;
				padding: 4px 8px;
				border-radius: 4px 8px;
				font-family: Arial;
				text-align: center;
				background-color: #202020;
				display:table; 
				margin:auto;
				animation-duration: 0.5s;
  				animation-name: slideinbottom;
			}

			.footer {
				display: inline;
				margin: 0px;
				padding: 8px;
				font-family: Arial;
				position: fixed;
				left: 0;
				bottom: 0;
				width: 100%;
				background-color: #2D2D2D;
				color: white;
				text-align: center;
				animation-duration: 0.5s;
  				animation-name: slideinbottom;
			}

			@keyframes slidein {
			  from {
			    transform: translateY(-200%);
			  }

			  to {
			    transform: translateY(0%);
			  }
			}

			@keyframes slideinbottom {
			  from {
			    transform: translateY(200%);
			  }

			  to {
			    transform: translateY(0%);
			  }
			}
		</style>
	</header>
	<body style="background-color:#202020;">
		<div class = "TitleBar"> 
			<p style = "float: left; margin-left: 16px;" class = "TitleText">repository</p>
			<p style = "float: left; margin-left: 0px;" class = "TitleText">portfolio</p>
			<p><a style = "float: right; margin-top: -8px; margin-right: 16px;" class = "TitleText" href="https://github.com/LoggyDev?tab=repositories/" target="_blank">github</a></p>
		</div>
			<p id = "fileData"></p>
			<center> <iframe class = "video" width="908" height="511" src="https://www.youtube.com/embed/AdC1nAJOGOI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>
		<div class="footer">
		  <p class = "title">loggyDev 2021</p>
		</div>
	</body>
</html>

