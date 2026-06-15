<!DOCTYPE html>
<html>
<head>
<style>

.container {
    width: 700px;
    border: 1px solid black;
    padding: 20px;
    margin: auto;
}

h1 {
    text-align: center;
}

.nba-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 12px;
}

.card {
    height: 250px;
    border: 1px solid gray;
    text-align: center;
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.name {
    font-weight: bold;
    margin-top: 5px;
}

</style>
</head>

<body>

<div class="container">

<h1>My Top 10 Favorite NBA Players</h1>

<div class="nba-grid">

<div class="card">
<img src="Russ.avif">
<div class="name">Russell Westbrook</div>
</div>

<div class="card">
<img src="curry.jpg">
<div class="name">Stephen Curry</div>
</div>

<div class="card">
<img src="jordan.jpg">
<div class="name">Michael Jordan</div>
</div>

<div class="card">
<img src="kobe.jpg">
<div class="name">Kobe Bryant</div>
</div>

<div class="card">
<img src="durant.jpg">
<div class="name">Kevin Durant</div>
</div>

<div class="card">
<img src="giannis.jpg">
<div class="name">Giannis Antetokounmpo</div>
</div>

<div class="card">
<img src="luka.jpg">
<div class="name">Luka Doncic</div>
</div>

<div class="card">
<img src="dennis.jpg">
<div class="name">Dennis Rodman</div>
</div>

<div class="card">
<img src="wade.jpg">
<div class="name">Dwayne wade</div>
</div>

<div class="card">
<img src="james.jpg">
<div class="name">Lebron james</div>
</div>

</div>

</div>

</body>
</html>
