<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Tours a Japón | Experiencias Privadas</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
    --primary:#111;
    --secondary:#e63946;
    --bg:#f6f6f6;
    --text:#333;
}

*{box-sizing:border-box;margin:0;padding:0;}

body{
    font-family:Arial, Helvetica, sans-serif;
    background:var(--bg);
    color:var(--text);
}

/* HEADER */
header{
    background:#000;
    color:#fff;
    padding:20px 0;
}
.header-container{
    max-width:1400px;
    margin:auto;
    padding:0 20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}
.logo{font-size:24px;font-weight:bold;}
nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-weight:bold;
}
nav a:hover{color:var(--secondary);}

/* HERO */
.hero{
    height:85vh;
    background:url("https://images.unsplash.com/photo-1549693578-d683be217e58") center/cover no-repeat;
    display:flex;
    align-items:center;
}
.hero-box{
    background:rgba(0,0,0,0.65);
    color:white;
    max-width:600px;
    padding:40px;
    border-radius:15px;
    margin-left:5%;
}
.hero-box h1{font-size:42px;}
.hero-box a{
    display:inline-block;
    margin-top:20px;
    background:var(--secondary);
    padding:12px 30px;
    border-radius:30px;
    color:white;
    text-decoration:none;
}

/* SECTIONS */
section{padding:80px 20px;}
.container{max-width:1400px;margin:auto;}
.section-title{text-align:center;margin-bottom:50px;}
.section-title h2{font-size:36px;}

/* TOURS */
.tours{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
}
.tour-card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 10px 25px rgba(0,0,0,0.1);
}
.tour-card img{
    width:100%;
    height:220px;
    object-fit:cover;
}
.tour-content{padding:25px;}
.price{color:var(--secondary);font-weight:bold;margin-top:10px;}
.spec{font-size:14px;color:#777;margin-top:5px;}

/* PAYMENTS */
.payments{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}
.payments a{
    padding:15px 30px;
    border-radius:40px;
    text-decoration:none;
    font-weight:bold;
    color:white;
}
.paypal{background:#003087;}
stripe{background:#635bff;}

/* CONTACT */
.contact{
    background:#000;
    color:white;
    text-align:center;
    padding:60px 20px;
}

/* FOOTER */
footer{
    background:#000;
    color:#aaa;
    text-align:center;
    padding:20px;
}

/* WHATSAPP */
.whatsapp{
    position:fixed;
    bottom:25px;
    right:25px;
    background:#25d366;
    color:white;
    padding:15px 18px;
    border-radius:50%;
    font-size:22px;
    text-decoration:none;
}
</style>
</head>

<body>

<header>
    <div class="header-container">
        <div class="logo">Tours a Japón</div>
        <nav>
            <a href="#tours">Tours</a>
            <a href="#payment">Pagos</a>
            <a href="#contact">Contacto</a>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="hero-box">
        <h1>Vive Japón como un local</h1>
        <p>Tours privados en español, seguros y personalizados</p>
        <a href="#tours">Ver tours</a>
    </div>
</section>

<section id="tours">
<div class="container">
<div class="section-title">
<h2>Tours Disponibles</h2>
</div>

<div class="tours">

<div class="tour-card">
<img src="https://images.unsplash.com/photo-1503899036084-c55cdd92da26">
<div class="tour-content">
<h3>Tour nocturno (6 horas)</h3>
<p>Luces, barrios icónicos y Japón nocturno.</p>
<div class="price">¥30,000</div>
</div>
</div>

<div class="tour-card">
<img src="https://images.unsplash.com/photo-1545569341-9eb8b30979d9">
<div class="tour-content">
<h3>Hakone & Monte Fuji</h3>
<p>Naturaleza, lago Ashi y vistas al Fuji.</p>
<div class="price">¥50,000</div>
</div>
</div>

<div class="tour-card">
<img src="https://images.unsplash.com/photo-1518544887879-8b8f9d4d40b1">
<div class="tour-content">
<h3>Tour Daikoku</h3>
<p>Encuentro de autos más famoso de Japón.</p>
<div class="price">¥15,000 por persona</div>
<div class="spec">Mínimo 3 personas</div>
</div>
</div>

</div>
</div>
</section>

<section id="payment">
<div class="container">
<div class="section-title">
<h2>Métodos de Pago</h2>
<p>Paga de forma segura desde cualquier país</p>
</div>

<div class="payments">
<a class="paypal" href="PEGA_AQUI_TU_LINK_PAYPAL" target="_blank">Pagar con PayPal</a>
<a class="paypal" style="background:#635bff" href="PEGA_AQUI_TU_LINK_STRIPE" target="_blank">Tarjeta de crédito</a>
</div>
</div>
</section>

<section id="contact" class="contact">
<h2>Contacto Directo</h2>
<p>Respuesta rápida por WhatsApp</p>
<a href="https://wa.me/817084950211" style="color:white;font-size:20px;">📲 WhatsApp</a>
</section>

<footer>
© 2026 Tours a Japón
</footer>

<a class="whatsapp" href="https://wa.me/817084950211">💬</a>

</body>
</html>


<a class="whatsapp" href="https://wa.me/XXXXXXXXXX">💬</a>

</body>
</html>
