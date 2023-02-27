# repocontainer


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

