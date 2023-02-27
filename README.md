# repocontainer
 

<!DOCTYPE html>
<html>
<head>
	<title>Vetrina Divani</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<nav>
			<div class="logo">
				<a href="#">Vetrina Divani</a>
			</div>
			<ul class="nav-links">
				<li><a href="#">Home</a></li>
				<li><a href="#">Prodotti</a></li>
				<li><a href="#">Contatti</a></li>
			</ul>
			<div class="burger">
				<div class="line"></div>
				<div class="line"></div>
				<div class="line"></div>
			</div>
		</nav>
	</header>

	<main>
		<section class="sofa-container">
			<!-- qui inserisci il codice per i divani -->
		</section>
	</main>

	<footer>
		<p>Copyright © Vetrina Divani
	</footer>

	<script src="app.js"></script>
</body>
</html>




body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #333;
	color: #fff;
	padding: 10px;
}

nav {
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between;
	align-items: center;
}

.logo a {
	color: #fff;
	font-size: 1.5em;
	text-decoration: none;
}

.nav-links {
	display: flex;
	flex-wrap: wrap;
	list-style: none;
	margin: 0;
	padding: 0;
}

.nav-links li {
	margin: 0 10px;
}

.nav-links a {
	color: #fff;
	text-decoration: none;
	text-transform: uppercase;
	font-weight: bold;
}

.burger {
	display: none;
	cursor: pointer;
}

.burger .line {
	width: 25px;
	height: 3px;
	background-color: #fff;
	margin: 5px;
}

@media screen and (max-width: 768px) {
	.nav-links {
		display: none;
		flex-direction: column;
		align-items: center;
		width: 100%;
		position: absolute;
		top: 60px;
		left: 0;
	}

	.nav-links li {
		width: 100%;
		text-align: center;
		margin: 5px 0;
	}

	.burger {
		display: block;
		position: absolute;
		top: 10px;
		right: 10px;
	}

	header {
		position: relative;
	}
}


<!DOCTYPE html>
<html>
<head>
	<title>Vetrina Divani</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>VETRINA DIVANI</h1>
	</header>

	<main>
		<section class="sofa-container">
			<div class="sofa-card">
				<img src="https://via.placeholder.com/300" alt="Divano 1">
				<h3>Divano 1</h3>
				<p>Descrizione del divano 1.</p>
				<button>Aggiungi al carrello</button>
			</div>

			<div class="sofa-card">
				<img src="https://via.placeholder.com/300" alt="Divano 2">
				<h3>Divano 2</h3>
				<p>Descrizione del divano 2.</p>
				<button>Aggiungi al carrello</button>
			</div>

			<div class="sofa-card">
				<img src="https://via.placeholder.com/300" alt="Divano 3">
				<h3>Divano 3</h3>
				<p>Descrizione del divano 3.</p>
				<button>Aggiungi al carrello</button>
			</div>
		</section>
	</main>

	<footer>
		<p>Copyright © Vetrina Divani
	</footer>
</body>
</html>



body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #333;
	color: #fff;
	padding: 10px;
	text-align: center;
}

main {
	margin: 20px auto;
	max-width: 960px;
}

.sofa-container {
	display: flex;
	flex-wrap: wrap;
	justify-content: space-between;
}

.sofa-card {
	background-color: #fff;
	border: 1px solid #ddd;
	box-shadow: 2px 2px 5px #ccc;
	margin-bottom: 20px;
	padding: 10px;
	text-align: center;
	width: 30%;
}

.sofa-card img {
	display: block;
	margin: 0 auto;
	max-width: 100%;
}

.sofa-card h3 {
	font-size: 1.5em;
	margin-top: 10px;
}

.sofa-card p {
	margin: 10px 0;
}

button {
	background-color: #333;
	border: none;
	color: #fff;
	cursor: pointer;
	padding: 10px;
	transition: background-color 0.3s ease;
}

button:hover {
	background-color: #666;
}

