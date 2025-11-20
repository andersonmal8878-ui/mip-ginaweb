<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calzado SM</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #fbe4ff;
        }

        /* Encabezado */
        header {
            background: linear-gradient(135deg, #d279ff, #ff8ac9);
            color: white;
            padding: 40px;
            text-align: center;
        }

        /* Logo SM */
        .logo {
            width: 100px;
            height: 100px;
            margin: 0 auto 15px auto;
            background: white;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #d279ff;
            font-size: 40px;
            font-weight: bold;
            border: 5px solid #ff8ac9;
        }

        /* Menú */
        nav {
            background: #d279ff;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        /* Secciones */
        section {
            padding: 30px;
            max-width: 900px;
            margin: auto;
            background: white;
            margin-top: 20px;
            border-radius: 12px;
            box-shadow: 0 0 10px #e5b3ff;
        }

        /* Productos */
        .productos {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .producto {
            background: #fde1f4;
            border-radius: 10px;
            padding: 15px;
            width: 250px;
            text-align: center;
            border: 2px solid #ff8ac9;
        }

        footer {
            background: #ff8ac9;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <div class="logo">SM</div>
    <h1>Calzado SM</h1>
    <p>Moda • Estilo • Confort</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Catálogo</a>
    <a href="#">Ofertas</a>
    <a href="#">Contacto</a>
</nav>

<section>
    <h2>Sobre Nosotros</h2>
    <p>
        En <strong>Calzado SM</strong> ofrecemos calzado moderno, cómodo y de excelente calidad para todas las edades.
        Combinamos estilo, tendencia y precios accesibles.
    </p>
</section>

<section>
    <h2>Productos Destacados</h2>

    <div class="productos">
        <div class="producto">
            <h3>Sandalias Dama</h3>
            <p>Modelos modernos y cómodos.</p>
            <strong>$20.00</strong>
        </div>

        <div class="producto">
            <h3>Zapatos Casual</h3>
            <p>Para uso diario con estilo.</p>
            <strong>$15.00</strong>
        </div>

        <div class="producto">
            <h3>Calzado Niño</h3>
            <p>Resistentes y confortables.</p>
            <strong>$10.00</strong>
        </div>
    </div>
</section>

<section>
    <h2>Contacto</h2>
    <p><strong>WhatsApp:</strong> +593 969680783</p>
    <p><strong>Dirección:</strong> Malchinguí </p>
</section>

<footer>
    <p> 2025 Calzado SM — Todos los derechos reservados</p>
</footer>

</body>
</html>

