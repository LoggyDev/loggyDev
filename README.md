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


