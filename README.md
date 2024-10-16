<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Funeraria Santoyo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            text-align: center;
            padding: 10px;
            background-color: #555;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .hero {
            background-image: url('funeraria.jpg');
            background-size: cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }
        .container {
            padding: 20px;
        }
        .service-box {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        .service-box h2 {
            margin-top: 0;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 15px;
            background-color: #333;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Funeraria Santoyo</h1>
        <p>Acompañamos a su familia en los momentos más difíciles</p>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Paquetes Funerarios</a>
        <a href="#">Servicios Personalizados</a>
        <a href="#">Contáctenos</a>
    </nav>

    <div class="hero">
        <h1>Un servicio con respeto y dignidad</h1>
    </div>

    <div class="container">
        <div class="service-box">
            <h2>Plan Básico</h2>
            <p>Incluye: Atención las 24 horas, asesoría en trámites legales, servicio de sala de velación, transporte del cuerpo, ataúd estándar.</p>
            <a href="#" class="btn">Más Información</a>
        </div>

        <div class="service-box">
            <h2>Plan Intermedio</h2>
            <p>Incluye todo lo del Plan Básico, además de: ataúd de mejor calidad, capilla para ceremonia religiosa y arreglos florales.</p>
            <a href="#" class="btn">Más Información</a>
        </div>

        <div class="service-box">
            <h2>Plan Premium</h2>
            <p>Incluye todo lo del Plan Intermedio, además de: ataúd de lujo, ceremonia personalizada y recordatorios conmemorativos.</p>
            <a href="#" class="btn">Más Información</a>
        </div>
    </div>

    <footer>
        <p>© 2024 Funeraria Santoyo. Todos los derechos reservados.</p>
        <p>Contacto: 555-1234 | contacto@funerariasantoyo.com</p>
    </footer>

</body>
</html>
