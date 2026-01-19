
<head>
<meta charset="UTF-8">
<title> TOURS A JAPON  | Experiencias Privadas</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{ --primary:#111;
    --secondary:#e63946;
    --bg:#f6f6f6;
    --text:#333;
}

*{ box-sizing:border-box;
    margin:0;
    padding:0;
}

body{  font-family: Arial, Helvetica, sans-serif;
    background:var(--bg);
    color:var(--text);
    line-height:1.6;
}

/* ---------- HEADER ---------- */
header{background:var(--primary);
    color:#fff;
    padding:20px 0;
}

.header-container{ max-width:1400px;
    margin:auto;
    padding:0 20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{ font-size:24px;
    font-weight:bold;
}

nav a{ color:#fff;
    text-decoration:none;
    margin-left:20px;
    font-weight:bold;
}
nav a:hover{ color:var(--secondary);
}

/* ---------- HERO ---------- */
.hero{height:85vh;
    background:url("https://images.unsplash.com/photo-1549693578-d683be217e58") center/cover no-repeat;
    display:flex;
    align-items:center;
}

.hero-content{max-width:1400px;
    margin:auto;
    padding:0 20px;
    color:white;
}

.hero-box{background:rgba(0,0,0,0.65);
    max-width:600px;
    padding:40px;
    border-radius:12px;
}

.hero-box h1{font-size:42px;
    margin-bottom:15px;
}

.hero-box p{font-size:18px;
}

.hero-box a{display:inline-block;
    margin-top:20px;
    background:var(--secondary);
    color:white;
    padding:12px 25px;
    border-radius:30px;
    text-decoration:none;
    font-weight:bold;
}

/* ---------- SECTIONS ---------- */
section{padding:80px 20px;
}

.container{ max-width:1400px;
    margin:auto;
}

.section-title{ text-align:center;
    margin-bottom:50px;
}

.section-title h2{font-size:36px;
    margin-bottom:10px;
}

.section-title p{ color:#666;
}

/* ---------- TOURS ---------- */
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

.tour-card-content{
    padding:25px;
}

.tour-card h3{
    margin-bottom:10px;
}

.tour-card p{
    font-size:15px;
    color:#555;
}

.price{
    margin-top:15px;
    font-weight:bold;
    color:var(--secondary);
}

/* ---------- ABOUT ---------- */
.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
}

.about img{
    width:100%;
    border-radius:15px;
}

/* ---------- WHY ---------- */
.why{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
    text-align:center;
}

.why div{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 8px 20px rgba(0,0,0,0.1);
}

/* ---------- CONTACT ---------- */
.contact{
    background:var(--primary);
    color:white;
    text-align:center;
    padding:60px 20px;
}

.contact a{
    display:inline-block;
    margin-top:20px;
    background:var(--secondary);
    color:white;
    padding:15px 35px;
    border-radius:40px;
    text-decoration:none;
    font-size:18px;
}

/* ---------- FOOTER ---------- */
footer{
    background:#000;
    color:#aaa;
    text-align:center;
    padding:20px;
}

/* ---------- WHATSAPP ---------- */
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
    box-shadow:0 5px 15px rgba(0,0,0,0.3);
}

/* ---------- RESPONSIVE ---------- */
@media(max-width:900px){
    .about{
        grid-template-columns:1fr;
    }
    .hero-box h1{
        font-size:32px;
    }
}
</style>
</head>

<body>

<header>
    <div class="header-container">
        <div class="logo">TOUR A JAPON </div>
        <nav>
            <a href="#tours">TOURS </a>
            <a href="#about">SOBRE NOSOTROS </a>
            <a href="#contact">CONTACTO </a>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="hero-content">
        <div class="hero-box">
            <h1>Explora Japón con un guía profesional</h1>
            <p>Tours privados, personalizados y en español por todo Japón.</p>
            <a href="#contact">Reservar ahora</a>
        </div>
    </div>
</section>

<section id="tours">
    <div class="container">
        <div class="section-title">
            <h2>Tours Destacados</h2>
            <p>Experiencias únicas diseñadas para ti</p>
        </div>

        <div class="tours">
            <div class="tour-card">
                <img src="https://images.unsplash.com/photo-1526481280690-7ead49f4a3b8">
                <div class="tour-card-content">
                    <h3>Tokyo Full Day</h3>
                    <p>Asakusa, Shibuya, Meiji, Harajuku y más.</p>
                    <div class="price">Desde ¥35,000</div>
                </div>
            </div>

            <div class="tour-card">
                <img src="https://images.unsplash.com/photo-1503899036084-c55cdd92da26">
                <div class="tour-card-content">
                    <h3>Hakone & Monte Fuji</h3>
                    <p>Naturaleza, onsen y vistas icónicas.</p>
                    <div class="price">Desde ¥45,000</div>
                </div>
            </div>

            <div class="tour-card">
                <img src="https://images.unsplash.com/photo-1545569341-9eb8b30979d9">
                <div class="tour-card-content">
                    <h3>Kyoto & Nara</h3>
                    <p>Templos, geishas y la historia de Japón.</p>
                    <div class="price">Desde ¥50,000</div>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="about">
    <div class="container about">
        <img src="https://images.unsplash.com/photo-1554797589-7241bb691973">
        <div>
            <h2>Sobre mí</h2>
            <p>Soy guía profesional residente en Japón, con amplia experiencia guiando viajeros de Latinoamérica y España. Mi objetivo es que vivas Japón de forma auténtica, cómoda y sin estrés.</p>
        </div>
    </div>
</section>

<section>
    <div class="container">
        <div class="section-title">
            <h2>¿Por qué elegirnos?</h2>
        </div>
        <div class="why">
            <div>✔️ Guía en español</div>
            <div>✔️ Tours privados</div>
            <div>✔️ Itinerarios flexibles</div>
            <div>✔️ Asistencia total</div>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contáctanos</h2>
    <p>Reserva tu experiencia personalizada en Japón</p>
    <a href="https://wa.me/XXXXXXXXXX">WhatsApp</a>
</section>

<footer>
    © 2026 Tours a Japón | Todos los derechos reservados
</footer>

<a class="whatsapp" href="https://wa.me/XXXXXXXXXX">💬</a>

</body>
</html>
