<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Renacer Español</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #d62839;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        header img {
            max-height: 50px;
        }
        nav {
            background-color: #f1f1f1;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: #333;
            text-decoration: none;
        }
        .banner {
            background: url('banner.jpg') no-repeat center center;
            background-size: cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .section {
            padding: 20px;
            margin: 0 10px;
        }
        .section img {
            max-width: 100%;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            background-color: #f1f1f1;
            padding: 10px;
            text-align: center;
        }
        footer a {
            color: #333;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Renacer Español">
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sobre-nosotros">Sobre Nosotros</a>
        <a href="#valores">Valores</a>
        <a href="#propuestas">Propuestas</a>
        <a href="#noticias">Noticias</a>
        <a href="#unete">Únete</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="banner">
        <h1>Un Nuevo Comienzo para España</h1>
        <p>Por la soberanía y el honor español</p>
        <a href="#unete" style="background-color: #f1f1f1; color: #d62839; padding: 10px 20px; text-decoration: none; border-radius: 5px;">Únete a Nosotros</a>
    </div>
    <div id="inicio" class="section">
        <h2>Bienvenido a Renacer Español</h2>
        <p>Somos una nueva fuerza política comprometida con un futuro en el que todos los españoles puedan prosperar. Nuestro objetivo es recuperar el orgullo nacional, defender nuestros valores y construir una España unida y fuerte.</p>
    </div>
    <div id="sobre-nosotros" class="section">
        <h2>Quiénes Somos</h2>
        <img src="foto-equipo.jpg" alt="Equipo Renacer Español">
        <p>Renacer Español es el nuevo partido político que surge con la visión de devolver a España su grandeza y unidad. Fundado por José Luis Palacios San Emeterio, el partido nace con el compromiso de representar los verdaderos intereses de los ciudadanos, promoviendo un nuevo comienzo basado en los principios de esfuerzo, libertad, justicia y hermandad.</p>
    </div>
    <div id="valores" class="section">
        <h2>Nuestros Valores</h2>
        <h3>Esfuerzo</h3>
        <p>Creemos en el valor del trabajo duro y la meritocracia como motores del progreso. Apoyamos a quienes construyen nuestro futuro con dedicación y talento.</p>
        <h3>Libertad</h3>
        <p>Defendemos la libertad económica y la autonomía individual, garantizando que cada ciudadano pueda vivir y emprender según sus convicciones, sin intervenciones innecesarias.</p>
        <h3>Justicia</h3>
        <p>Luchamos por una justicia firme e imparcial que proteja a todos los ciudadanos y combata la corrupción con determinación.</p>
        <h3>Hermandad</h3>
        <p>Promovemos la unidad y el respeto mutuo entre todos los españoles, valorando la diversidad como una fortaleza y trabajando juntos por un bien común.</p>
    </div>
    <div id="propuestas" class="section">
        <h2>Nuestras Propuestas</h2>
        <h3>Economía</h3>
        <p>Fomentaremos políticas que impulsen la economía nacional, apoyen a los emprendedores y garanticen la creación de empleo.</p>
        <h3>Seguridad</h3>
        <p>Fortaleceremos las fuerzas de seguridad y mejoraremos la justicia para garantizar un entorno seguro y justo para todos.</p>
        <h3>Educación</h3>
        <p>Invertiremos en educación para ofrecer a nuestros jóvenes las mejores oportunidades y prepararles para los retos del futuro.</p>
        <h3>Salud</h3>
        <p>Nos comprometemos a mejorar el sistema de salud, asegurando acceso y calidad para todos los ciudadanos.</p>
    </div>
    <div id="noticias" class="section">
        <h2>Últimas Noticias</h2>
        <p>Mantente informado sobre nuestras actividades, eventos y noticias importantes.</p>
        <!-- Aquí puedes agregar un blog o lista de noticias -->
    </div>
    <div id="unete" class="section">
        <h2>Únete a Renacer Español</h2>
        <p>Si compartes nuestra visión y deseas formar parte de este nuevo comienzo, te invitamos a unirte a nuestro movimiento.</p>
        <form action="submit_form.php" method="post">
            <div class="form-group">
                <label for="nombre">Nombre Completo</label>
                <input type="text" id="nombre" name="nombre" required>
            </div>
            <div class="form-group">
                <label for="email">Correo Electrónico</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="telefono">Teléfono</label>
                <input type="tel" id="telefono" name="telefono">
            </div>
            <div class="form-group">
                <label for="mensaje">Mensaje Opcional</label>
                <textarea id="mensaje" name="mensaje"></textarea>
            </div>
            <button type="submit">Enviar</button>
        </form>
    </div>
    <div id="contacto" class="section">
        <h2>Contacto</h2>
        <p>Para más información o consultas, no dudes en contactarnos.</p>
        <p><strong>Dirección:</strong> [Dirección de la sede del partido]</p>
        <p><strong>Teléfono:</strong> [Número de contacto]</p>
        <p><strong>Correo Electrónico:</strong> <a href="mailto:info@renaceresp.com">info@renaceresp.com</a></p>
        <form action="submit_contact_form.php" method="post">
            <div class="form-group">
                <label for="contacto-nombre">Nombre Completo</label>
                <input type="text" id="contacto-nombre" name="contacto-nombre" required>
            </div>
            <div class="form-group">
                <label for="contacto-email">Correo Electrónico</label>
                <input type="email" id="contacto-email" name="contacto-email" required>
            </div>
            <div class="form-group">
                <label for="contacto-asunto">Asunto</label>
                <input type="text" id="contacto-asunto" name="contacto-asunto" required>
            </div>
            <div class="form-group">
                <label for="contacto-mensaje">Mensaje</label>
                <textarea id="contacto-mensaje" name="contacto-mensaje" required></textarea>
            </div>
            <button type="submit">Enviar</button>
        </form>
    </div>
    <footer>
        <p><a href="#inicio">Inicio</a> | <a href="#sobre-nosotros">Sobre Nosotros</a> | <a href="#valores">Valores</a> | <a href="#propuestas">Propuestas</a> | <a href="#noticias">Noticias</a> | <a href="#unete">Únete</a
