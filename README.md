# solidapp
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Solid App - Conectando Corazones, Transformando Vidas</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            line-height: 1.6;
            color: #333;
        }

        nav {
            background-color: #4CAF50;
            padding: 10px 20px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 60px 20px;
            text-align: center;
        }

        #inicio {
            background: #e0f7fa;
            color: #00796b;
            padding: 100px 20px;
        }

        #inicio h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        #inicio p {
            font-size: 1.2em;
            margin-bottom: 40px;
        }

        #inicio a {
            background-color: #00796b;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin: 10px;
            display: inline-block;
        }

        #inicio a:hover {
            background-color: #004d40;
        }

        h2 {
            color: #4CAF50;
            margin-bottom: 20px;
        }

        section p, section ol, section ul {
            max-width: 800px;
            margin: 0 auto 40px auto;
        }

        ol, ul {
            text-align: left;
        }

        ol li, ul li {
            margin-bottom: 10px;
        }

        form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }

        form label {
            display: block;
            margin-bottom: 5px;
        }

        form input, form textarea, form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        form button {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        form button:hover {
            background-color: #45a049;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        footer ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        footer ul li {
            display: inline;
            margin-right: 15px;
        }

        footer ul li a {
            color: white;
            text-decoration: none;
        }

        footer p {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <!-- Menú de Navegación -->
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
            <li><a href="#como-funciona">Cómo Funciona</a></li>
            <li><a href="#donar">Donar</a></li>
            <li><a href="#obtener-ayuda">Obtener Ayuda</a></li>
            <li><a href="#recursos">Recursos</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <!-- Sección: Banner Principal -->
    <section id="inicio">
        <h1>Solid App: Conectando Corazones, Transformando Vidas</h1>
        <p>Una plataforma para donar y recibir alimentos, ropa y recursos esenciales. Juntos, construimos una comunidad solidaria.</p>
        <a href="#descargar-app">Descargar la App</a>
        <a href="#sobre-nosotros">Más Información</a>
    </section>

    <!-- Sección: Sobre Nosotros -->
    <section id="sobre-nosotros">
        <h2>¿Qué es Solid App?</h2>
        <p>Solid App es una plataforma innovadora diseñada para conectar a donantes con personas de bajos recursos. Facilitamos el acceso a alimentos, ropa y otros recursos esenciales de manera gratuita o a precios reducidos, promoviendo la solidaridad y mejorando la calidad de vida en nuestras comunidades.</p>
    </section>

    <!-- Sección: Cómo Funciona -->
    <section id="como-funciona">
        <h2>¿Cómo Funciona?</h2>
        <ol>
            <li><strong>Donar:</strong> Regístrate y dona alimentos no perecederos, ropa en buen estado y otros artículos básicos.</li>
            <li><strong>Buscar Recursos:</strong> Los beneficiarios pueden buscar y encontrar los recursos que necesitan según su ubicación y disponibilidad.</li>
            <li><strong>Programar Entrega/Recogida:</strong> Coordina la entrega o recogida de los artículos donados de manera fácil y segura.</li>
            <li><strong>Recibir Apoyo Adicional:</strong> Accede a información sobre servicios sociales, talleres educativos y consejos para el cuidado de la salud.</li>
        </ol>
        <a href="#descargar-app">Descargar la App</a>
    </section>

    <!-- Sección: Donar -->
    <section id="donar">
        <h2>¡Haz la Diferencia! Dona Hoy</h2>
        <p>Con tu ayuda, podemos ofrecer recursos esenciales a quienes más lo necesitan. Únete a nuestra comunidad de donantes y ayuda a transformar vidas.</p>
        <a href="#donar-ahora">Donar Ahora</a>
    </section>

    <!-- Sección: Obtener Ayuda -->
    <section id="obtener-ayuda">
        <h2>¿Necesitas Ayuda?</h2>
        <p>Accede a alimentos, ropa y otros recursos esenciales de manera gratuita o a precios reducidos. Regístrate y encuentra lo que necesitas hoy mismo.</p>
        <a href="#registrarse">Registrarse</a>
    </section>

    <!-- Sección: Recursos -->
    <section id="recursos">
        <h2>Recursos Adicionales</h2>
        <ul>
            <li>Información sobre Servicios Sociales</li>
            <li>Talleres Educativos</li>
            <li>Consejos para el Cuidado de la Salud</li>
        </ul>
        <a href="#ver-mas">Ver Más</a>
    </section>

    <!-- Sección: Contacto -->
    <section id="contacto">
        <h2>Contáctanos</h2>
        <p>¿Tienes alguna pregunta? ¿Quieres saber más sobre cómo puedes ayudar o recibir ayuda? ¡Estamos aquí para ti!</p>
        <form action="#formulario-contacto" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Pie de Página -->
    <footer>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
            <li><a href="#como-funciona">Cómo Funciona</a></li>
            <li><a href="#donar">Donar</a></li>
            <li><a href="#obtener-ayuda">Obtener Ayuda</a></li>
            <li><a href="#recursos">Recursos</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
        <p>© 2024 Solid App. Todos los derechos reservados.</p>
        <p>Síguenos: <a href="#facebook">Facebook</a> <a href="#twitter">Twitter</a> <a href="#instagram">Instagram</a></p>
    </footer>
</body>
</html>
