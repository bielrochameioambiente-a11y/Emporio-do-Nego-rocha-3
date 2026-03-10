<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Empório do Nego Rocha</title>

<style>
body{
margin:0;
font-family:Arial;
background:#f4f4f4;
}

header{
background:#0b3d2e;
color:white;
padding:20px;
text-align:center;
}

header img{
width:160px;
}

nav{
background:#145c43;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
}

.hero{
height:400px;
background-image:url('https://images.unsplash.com/photo-1604719312566-8912e9227c6a');
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
color:white;
font-size:40px;
text-shadow:2px 2px 10px black;
}

.section{
padding:50px;
text-align:center;
}

.produtos{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}

.card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 5px 10px rgba(0,0,0,0.1);
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25d366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
box-shadow:0 5px 10px rgba(0,0,0,0.2);
}

footer{
background:#0b3d2e;
color:white;
padding:30px;
text-align:center;
}
</style>
</head>

<body>

<header>
<img src="logo.png">
<h1>Empório do Nego Rocha</h1>
<p>Qualidade e tradição desde 2019</p>
</header>

<nav>
<a href="#">Início</a>
<a href="#produtos">Produtos</a>
<a href="#contato">Contato</a>
</nav>

<div class="hero">
Empório do Nego Rocha
</div>

<section class="section">
<h2>Sobre o Empório</h2>

<p>
O Empório do Nego Rocha oferece produtos de qualidade,
bebidas, carvão, gelo e muito mais para atender você
com tradição e confiança.
</p>

</section>

<section class="section" id="produtos">

<h2>Produtos</h2>

<div class="produtos">

<div class="card">
<h3>Bebidas</h3>
<p>Cervejas, refrigerantes e muito mais</p>
</div>

<div class="card">
<h3>Carvão</h3>
<p>Perfeito para seu churrasco</p>
</div>

<div class="card">
<h3>Gelo</h3>
<p>Sempre disponível para sua bebida</p>
</div>

<div class="card">
<h3>Produtos de Empório</h3>
<p>Itens selecionados de qualidade</p>
</div>

</div>

</section>

<section class="section" id="contato">

<h2>Contato</h2>

<p><b>Telefone / WhatsApp</b></p>
<p>📞 (17) 99167-2624</p>

<p><b>Endereço</b></p>

<p>
Avenida José Rodrigues da Silva, 482A<br>
Olímpia - SP
</p>

</section>

<a class="whatsapp"
href="https://wa.me/5517991672624"
target="_blank">
WhatsApp
</a>

<footer>
<p>Empório do Nego Rocha © 2026</p>
</footer>

</body>
</html>
