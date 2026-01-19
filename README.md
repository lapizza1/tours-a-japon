# tours-a-japon
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tours a Japón</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f4f4;
            color: #333;
        }

        header {
            background: #111;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            background: #222;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1400px;
            margin: auto;
            padding: 40px 20px;
        }

        .hero {
            background: url("https://images.unsplash.com/photo-1549693578-d683be217e58") center/cover no-repeat;
            height: 400px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }

        .hero h1 {
            background: rgba(0,0,0,0.6);
            padding: 20px 30px;
            border-radius: 10px;
            font-size: 42px;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-top: 50px;
        }

        .card {
            background: white;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .card h3 {
            margin-top: 0;
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 60px;
        }
    </style>
</head>

<body>

<header>
    <h1>Tours a Japón 🇯🇵</h1>
    <p>Experiencias privadas y personalizadas</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Tours</a>
    <a href="#">Sobre mí</a>
    <a href="#">Contacto</a>
</nav>

<div class="container">

    <div class="hero">
        <h1>Descubre Japón como nunca antes</h1>
    </div>

    <div class="cards">
        <div class="card">
            <h3>Tokyo Clásico</h3>
            <p>Asakusa, Shibuya, Meiji y mucho más con guía en español.</p>
        </div>

        <div class="card">
            <h3>Hakone & Fuji</h3>
            <p>Vistas del Monte Fuji, onsen y naturaleza.</p>
        </div>

        <div class="card">
            <h3>Kyoto & Nara</h3>
            <p>Templos, geishas y la historia tradicional japonesa.</p>
        </div>
    </div>

</div>

<footer>
    <p>© 2026 Tours a Japón | Guía profesional en Japón</p>
</footer>

</body>
</html>
