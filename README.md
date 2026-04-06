<!DOCTYPE html>
<html lang="pt-BR">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Escola Brisa do Amanhã</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:Poppins;
color:#333;
}

/* CONTAINER */

.container{
max-width:1200px;
margin:auto;
padding:20px;
}

/* HEADER */

header{
background:white;
position:fixed;
width:100%;
top:0;
box-shadow:0 2px 10px rgba(0,0,0,0.1);
z-index:1000;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
display:flex;
align-items:center;
gap:10px;
font-weight:600;
font-size:20px;
}

.logo img{
height:45px;
border-radius:50%;
}

.nav-links{
display:flex;
gap:30px;
list-style:none;
}

.nav-links a{
text-decoration:none;
color:#333;
font-weight:500;
}

.cta{
background:#4facfe;
color:white;
padding:10px 20px;
border-radius:30px;
text-decoration:none;
}

/* HERO */

.hero{
height:100vh;
background:linear-gradient(135deg,#4facfe,#00f2fe);
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
padding-top:80px;
}

.hero img{
width:150px;
margin-bottom:20px;
border-radius:50%;
}

.hero h1{
font-size:45px;
margin-bottom:10px;
}

.hero p{
font-size:18px;
margin-bottom:25px;
}

.btn{
background:#ff6b6b;
padding:14px 30px;
border-radius:30px;
text-decoration:none;
color:white;
font-weight:600;
}

/* SECTIONS */

section{
padding:80px 20px;
}

.section-title{
text-align:center;
font-size:32px;
margin-bottom:50px;
}

/* SOBRE */

.sobre{
background:#f5f5f5;
text-align:center;
max-width:800px;
margin:auto;
}

/* DIFERENCIAIS */

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
margin-top:40px;
}

.feature{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 20px rgba(0,0,0,0.08);
text-align:center;
}

.feature i{
font-size:35px;
color:#4facfe;
margin-bottom:15px;
}

/* GALERIA */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
border-radius:10px;
}

/* CONTATO */

.contato{
background:#667eea;
color:white;
}

form{
max-width:500px;
margin:auto;
background:rgba(255,255,255,0.1);
padding:30px;
border-radius:15px;
}

input,textarea{
width:100%;
padding:12px;
margin-bottom:15px;
border:none;
border-radius:8px;
}

button{
width:100%;
padding:12px;
background:#ff6b6b;
border:none;
color:white;
border-radius:8px;
cursor:pointer;
}

/* WHATSAPP */

.whatsapp{
position:fixed;
bottom:25px;
right:25px;
background:#25D366;
width:60px;
height:60px;
display:flex;
align-items:center;
justify-content:center;
font-size:30px;
border-radius:50%;
color:white;
text-decoration:none;
box-shadow:0 5px 15px rgba(0,0,0,0.3);
}

/* FOOTER */

footer{
background:#222;
color:white;
text-align:center;
padding:25px;
}

</style>

</head>

<body>

<header>

<div class="container">

<nav>

<div class="logo">

<img src="logo.png">

Brisa do Amanhã

</div>

<ul class="nav-links">

<li><a href="#inicio">Início</a></li>

<li><a href="#sobre">Sobre</a></li>

<li><a href="#diferenciais">Diferenciais</a></li>

<li><a href="#contato">Contato</a></li>

</ul>

<a class="cta" href="#contato">Matricule-se</a>

</nav>

</div>

</header>


<section class="hero" id="inicio">

<div>

<img src="logo.png">

<h1>Escola Brisa do Amanhã</h1>

<p>Educação de qualidade para construir o futuro das nossas crianças</p>

<a class="btn" href="https://wa.me/5571984360107?text=Olá! Gostaria de informações sobre matrícula.">

Falar no WhatsApp

</a>

</div>

</section>


<section id="sobre">

<h2 class="section-title">Sobre a Escola</h2>

<div class="sobre">

<p>

Localizada em Santa Luzia, Salvador/BA, a Escola Brisa do Amanhã oferece ensino fundamental com foco no desenvolvimento intelectual, social e emocional das crianças.

</p>

<br>

<p>

📍 Av. Afrânio Peixoto, 508  
<br>
🕒 Segunda a Sexta – 07h às 17h

</p>

</div>

</section>


<section id="diferenciais">

<h2 class="section-title">Nossos Diferenciais</h2>

<div class="container">

<div class="features">

<div class="feature">

<i class="fas fa-graduation-cap"></i>

<h3>Professores Qualificados</h3>

<p>Equipe preparada para ensinar com dedicação.</p>

</div>

<div class="feature">

<i class="fas fa-book"></i>

<h3>Ensino de Qualidade</h3>

<p>Metodologia moderna focada no aprendizado.</p>

</div>

<div class="feature">

<i class="fas fa-child"></i>

<h3>Ambiente Seguro</h3>

<p>Espaço acolhedor para o desenvolvimento infantil.</p>

</div>

</div>

</div>

</section>


<section>

<h2 class="section-title">Galeria</h2>

<div class="container">

<div class="gallery">

<img src="https://images.unsplash.com/photo-1588072432836-e10032774350">

<img src="https://images.unsplash.com/photo-1509062522246-3755977927d7">

<img src="https://images.unsplash.com/photo-1524995997946-a1c2e315a42f">

</div>

</div>

</section>


<section class="contato" id="contato">

<h2 class="section-title">Entre em Contato</h2>

<form>

<input type="text" placeholder="Seu nome" required>

<input type="tel" placeholder="Telefone" required>

<input type="email" placeholder="Email">

<textarea placeholder="Mensagem"></textarea>

<button type="submit">Enviar mensagem</button>

</form>

</section>


<footer>

<p>

© Escola Brisa do Amanhã — Todos os direitos reservados

</p>

</footer>


<a class="whatsapp" href="https://wa.me/5571984360107?text=Olá! Gostaria de informações sobre matrícula." target="_blank">

<i class="fab fa-whatsapp"></i>

</a>


<script>

document.querySelector("form").addEventListener("submit",function(e){

e.preventDefault()

let nome=document.querySelector('input[type="text"]').value
let telefone=document.querySelector('input[type="tel"]').value
let email=document.querySelector('input[type="email"]').value
let mensagem=document.querySelector("textarea").value

let texto=`Olá! Meu nome é ${nome}%0A Telefone: ${telefone}%0A Email: ${email}%0A Mensagem: ${mensagem}`

window.open(`https://wa.me/5571984360107?text=${texto}`)

})

</script>

</body>
</html>
