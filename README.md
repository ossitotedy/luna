<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUBRAL - Restaurante</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0f0ff;
            color: #003366;
        }
        header {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
        }
        header img {
            width: 150px;
            display: block;
            margin: 0 auto;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #00509e;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: #003366;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            text-align: center;
        }
        .menu-item {
            background-color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .menu-item img {
            width: 100%;
            max-width: 300px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            background-color: #003366;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <img src="LOGO_LUBRAL_AZUL.png" alt="Logo de LUBRAL">
        <h1>LUBRAL - Pasión por la cocina</h1>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#menu">Menú</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="container" id="inicio">
        <h2>Bienvenidos a LUBRAL</h2>
        <p>Disfruta de la experiencia en LUBRAL el que va a ser tu restaurante favorito dentro de poco, contamos con una cocina y coctelería de autor donde juntamos los productos de nuestra tierra con técnicas innovadoras consiguiendo ofrecer una experiencia única y personalizada para cada uno de nuestros clientes
        
    .</p>
    </div>
    <div class="container" id="menu">
        <h2>Nuestro Menú</h2>
        <div class="menu-item">
            <h3>nuestro menú</h3>
            <img src="https://source.unsplash.com/300x200/?food" alt="Plato Especial">
            <p>Deliciosa especialidad de la casa con ingredientes frescos y sabores auténticos.</p>
        </div>
        <div class="menu-item">
            <h3>Postres Exquisitos</h3>
            <img src="https://source.unsplash.com/300x200/?dessert" alt="Postre Exquisito">
            <p>Endulza tu día con nuestros postres caseros.</p>
        </div>
    </div>
    <div class="container" id="contacto">
        <h2>Contacto</h2>
        <p>Visítanos en nuestra ubicación o llámanos al +123 456 7890.</p>
    </div>
    <footer>
        &copy; 2025 LUBRAL - Todos los derechos reservados.
    </footer>
</body>
</html>
