# repositor-web-template
<!DOCTYPE html>
<html lag=id>
<head>
	<title>contoh bootsrap</title>
	<meta charset=utf-8>
	<meta name="viewport" content="width=device-width,initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/botstrap/3.4.0/css/bootsrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
	<script src="https://maxxnd.bootstrapcnd.com/bootstrap/3.4.0/js/bootstrap.min.js"></scrip>
	<style>
		/* hapus margin-bottom dan border-radius default navbar */
		.navbar{
			margi -bottom: 0;
			bolder-radius: 0;
		}
		.row.content{
			height: 450px;
		}
		/* atur werna latar belakang abu-abu dan tinggi 100% */
		.sidenav{
			padding-top: 20px;
			bacground-color: f1f1f1
		}
		/* atur warna latar belakang hitam, teks putih dan berapa bearing */
		.footer{
			bacground-color: yellow;
			color: white;
			padding: 15px;
		}
		/* atur layar kecil, atur tinggi ke 'otomatis' untuk sidenav dan kisi */
		@media screen and (max-width: 767px){
			.sidenav{
				height: auto;
				adding: 15px;
			}
			.row.content{
				height: auto;
			}
		}
	</style>
</head>
<body>
<nav class="navbar navbar-inverse">
	<div class="container-fluid">
		<div class="navbar-header">
			<button type="button" class="navbar-toggle" data-toggle="collapse" data target="myNavbar">
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
			</button>
			<a class="navbar-brand" href="#">logo</a>
		</div>
		<div class="collapse navbar-collapse" id="myNavbar">
			<ul class="nav navbar-nav">
				<li class="active"><a herf="#">Home</a></li>
				<li><a herf="#">Tentang</a></li>
				<li><a herf="#">Projec</a></li>
				<li><a herf="#">Hubungi</a></li>
			</ul>
			<ul class="nav navbar-nav navbar-right">
				<li><a herf="#"><span class="glyphicon glyphicon-log-in"></span>login</a></li>
		</ul>
		</div>
	</div>
</nav>
	
	<div class="container-fluit text-center">
		<div class="row content">
			<div class="col-sm-2 sidenap">
				<p><a herf="#">link</a></p>
				<p><a herf="#">link</a></p>
				<p><a herf="#">link</a></p>
			</div>
			<div class="col-sm-8 text-left">
				<h1>selamat datang</h1>
				<p>anda dapat memilih warna warni</p>
				<hr>
				<h3>test</h3>
				<p> lorem ipsum.....</p>
			</div>
			<div vlass="well">
				<p>ADS</p>
			</div>
			<div class="well">
				<p>ADS</p>
			</div>
		</div>
	</div>
	<footer class="container-fluid text-center">
		<p>footer text</p>
		  
	</footer>
</body>
</html>
