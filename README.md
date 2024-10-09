
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta description="SkyWatcher: Instalación de sistemas de seguridad para empresas, residencias y negocios en Santa Ana, El Salvador.">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>SkyWatcher - Sistemas de Seguridad</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&family=Orbitron:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        /* Reset de estilos básicos */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Estilos generales */
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #121212;
            color: #ffffff;
            line-height: 1.6;
        }

        a {
            color: #00bcd4;
            text-decoration: none;
        }

        a:hover {
            color: #0097a7;
        }

        /* Encabezado */
        header {
            background-color: #1f1f1f;
            padding: 20px 0;
            text-align: center;
            position: relative;
        }

        header img {
            width: 150px;
            height: auto;
        }

        header h1 {
            font-family: 'Orbitron', sans-serif;
            margin-top: 10px;
            font-size: 2em;
            color: #00bcd4;
        }

        /* Navegación */
        nav {
            background-color: #333;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav a {
            padding: 15px 20px;
            display: block;
            color: #ffffff;
            font-weight: 500;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #575757;
        }

        /* Contenedor principal */
        .container {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Secciones */
        section {
            margin-bottom: 60px;
        }

        section h2 {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.8em;
            margin-bottom: 20px;
            color: #00bcd4;
            border-bottom: 2px solid #00bcd4;
            display: inline-block;
            padding-bottom: 5px;
        }

        section p, section ul {
            font-size: 1.1em;
            color: #cccccc;
        }

        /* Lista de valores y servicios */
        ul {
            list-style: none;
            padding-left: 0;
        }

        ul li {
            background: url('checkmark.png') no-repeat left center;
            background-size: 20px;
            padding-left: 30px;
            margin-bottom: 10px;
        }

        /* Ocultar todas las secciones excepto la de "Quiénes Somos" al inicio */
        #mision-vision, #valores, #servicios, #contacto, #instalaciones-equipos {
            display: none;
        }

        /* Contacto */
        .contact-info p {
            margin-bottom: 10px;
            font-size: 1.1em;
        }

        .contact-info a {
            color: #00bcd4;
        }

        /* Pie de página */
        footer {
            background-color: #1f1f1f;
            color: #cccccc;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            font-size: 1em;
        }

        /* Responsive */
        @media (max-width: 768px) {
            nav a {
                padding: 10px 15px;
                font-size: 0.9em;
            }

            header h1 {
                font-size: 1.5em;
            }

            section h2 {
                font-size: 1.5em;
            }

            .container {
                padding: 20px 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.jpg.jpg" alt="Logo SkyWatcher">
        <h1>SkyWatcher</h1>
    </header>

    <nav>
        <a href="#quienes-somos" onclick="showSection('quienes-somos')">Quiénes Somos</a>
        <a href="#mision-vision" onclick="showSection('mision-vision')">Misión y Visión</a>
        <a href="#valores" onclick="showSection('valores')">Valores</a>
        <a href="#servicios" onclick="showSection('servicios')">Servicios</a>
        <a href="#instalaciones-equipos" onclick="showSection('instalaciones-equipos')">Instalaciones y Equipos</a>
        <a href="#contacto" onclick="showSection('contacto')">Contacto</a>
    </nav>

    <div class="container">
        <!-- Quiénes Somos -->
        <section id="quienes-somos">
            <h2>Quiénes Somos</h2>
            <p>SkyWatcher es una empresa ubicada en Santa Ana, El Salvador, dedicada a la instalación de sistemas de seguridad para empresas, residenciales y negocios. 
               Nuestro equipo está conformado por Miguel Acuña, Luis Mancia, Fernando Benavides y Emerson Zometa, profesionales comprometidos con brindar soluciones de monitoreo eficientes y confiables.</p>
        </section>

        <!-- Misión y Visión -->
        <section id="mision-vision">
            <h2>Misión</h2>
            <p>Somos una empresa que provee servicios de instalaciones de sistemas de seguridad para el monitoreo de áreas específicas en sus empresas, negocios o zonas residenciales, eficientes y confiables instalados con profesionalismo y para cumplir con las expectativas de nuestros clientes.</p>
            
            <h2>Visión</h2>
            <p>Ser una empresa reconocida encargada del monitoreo y seguridad de los hogares y empresas salvadoreñas, cumpliendo con la transparencia y pasión de siempre; ofreciendo la mejor atención y calidad actualizando constantemente nuestros servicios.</p>
        </section>

        <!-- Valores -->
        <section id="valores">
            <h2>Valores</h2>
            <ul>
                <li>Integridad</li>
                <li>Innovación</li>
                <li>Responsabilidad</li>
                <li>Profesionalismo</li>
            </ul>
        </section>

        <!-- Servicios -->
        <section id="servicios">
            <h2>Servicios</h2>
            <ul>
                <li>Instalación de cámaras de seguridad</li>
                <li>Sensores de movimiento</li>
                <li>Sensores infrarrojos</li>
                <li>Cerraduras automáticas</li>
            </ul>
        </section>

        <!-- Instalaciones y Equipos -->
        <section id="instalaciones-equipos">
            <h2>Instalaciones y Equipos</h2>
            <div>
                <h3>Paquete Normal</h3>
                <p>Descripción y detalles del Paquete Normal irán aquí.</p>
            </div>
            <div>
                <h3>Paquete Plus</h3>
                <p>Descripción y detalles del Paquete Plus irán aquí.</p>
            </div>
            <div>
                <h3>Paquete Premium</h3>
                <p>Descripción y detalles del Paquete Premium irán aquí.</p>
            </div>
        </section>

        <!-- Contacto -->
        <section id="contacto">
            <h2>Contacto</h2>
            <p>Para más información sobre nuestros servicios, contáctanos a través de nuestras redes sociales o nuestro número de WhatsApp.</p>
            <div class="contact-info">
                <p><strong>Instagram:</strong> <a href="https://instagram.com/skywatcher_sv" target="_blank">@skywatcher_sv</a></p>
                <p><strong>WhatsApp:</strong> <a href="https://wa.me/50378500629" target="_blank">+503 7850 0629</a></p>
                <p><strong>Facebook:</strong> <a href="https://facebook.com/skywatcher_sv" target="_blank">SkyWatcher</a></p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 SkyWatcher. Todos los derechos reservados.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            // Ocultar todas las secciones
            document.querySelectorAll('section').forEach(section => {
                section.style.display = 'none';
            });
            // Mostrar la sección seleccionada
            document.getElementById(sectionId).style.display = 'block';
        }

        // Mostrar la sección "Quiénes Somos" por defecto
        showSection('quienes-somos');
    </script>
</body>
</html>
