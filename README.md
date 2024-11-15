# Ahorro
Lo mejor de lo mejor
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consultoría de Negocios</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
            color: white;
        }
        nav a {
            color: white;
            padding: 1rem;
            text-decoration: none;
        }
        nav a:hover {
            background: #575757;
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        .services, .success {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            margin: 1rem;
            width: 300px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #333;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        button {
            background: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Consultoría de Negocios</h1>
        <p>Impulsamos tu negocio hacia el éxito.</p>
        <button onclick="window.location.href='#contact'">Reserva tu consulta gratuita</button>
    </header>
    <nav>
        <a href="#about">Sobre Nosotros</a>
        <a href="#services">Servicios</a>
        <a href="#success">Casos de Éxito</a>
        <a href="#contact">Contacto</a>
    </nav>
    <section id="about">
        <h2>Sobre Nosotros</h2>
        <p>Somos un equipo de expertos dedicados a ofrecer soluciones estratégicas para negocios de todos los tamaños.</p>
    </section>
    <section id="services">
        <h2>Servicios</h2>
        <div class="services">
            <div class="card">
                <h3>Consultoría Estratégica</h3>
                <p>Planes personalizados para el crecimiento de tu negocio.</p>
            </div>
            <div class="card">
                <h3>Marketing Digital</h3>
                <p>Impulsa tu presencia online con estrategias innovadoras.</p>
            </div>
            <div class="card">
                <h3>Transformación Digital</h3>
                <p>Moderniza tu negocio con herramientas digitales.</p>
            </div>
        </div>
    </section>
    <section id="success">
        <h2>Casos de Éxito</h2>
        <div class="success">
            <div class="card">
                <h3>Cliente 1</h3>
                <p>Incrementamos sus ventas en un 50% con estrategias personalizadas.</p>
            </div>
            <div class="card">
                <h3>Cliente 2</h3>
                <p>Digitalizamos todos sus procesos para mejorar la eficiencia.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contacto</h2>
        <p>¿Listo para comenzar? Contáctanos hoy mismo.</p>
        <form>
            <label for="name">Nombre:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Correo Electrónico:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Mensaje:</label><br>
            <textarea id="message" name="message" rows="5" required></textarea><br><br>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Consultoría de Negocios. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
