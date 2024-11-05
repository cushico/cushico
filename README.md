<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil Profesional - Luis Enrique Jaramillo Montaño</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Luis Enrique Jaramillo Montaño</h1>
        <p>Especialista en Ciberseguridad y CEO de ISCD</p>
    </header>

    <nav>
        <ul>
            <li><a href="#inicio" onclick="showTab('inicio')">Inicio</a></li>
            <li><a href="#acerca" onclick="showTab('acerca')">Acerca de</a></li>
            <li><a href="#experiencia" onclick="showTab('experiencia')">Experiencia Profesional</a></li>
            <li><a href="#habilidades" onclick="showTab('habilidades')">Habilidades Técnicas</a></li>
            <li><a href="#certificaciones" onclick="showTab('certificaciones')">Certificaciones y Cursos</a></li>
            <li><a href="#contacto" onclick="showTab('contacto')">Contacto</a></li>
        </ul>
    </nav>

    <main>
        <section id="inicio" class="tab-content">
            <h2>Bienvenido</h2>
            <p>Bienvenido a la página profesional de Luis Enrique Jaramillo Montaño. Aquí encontrarás información sobre mi experiencia en ciberseguridad, educación y proyectos.</p>
        </section>

        <section id="acerca" class="tab-content" style="display:none;">
            <h2>Acerca de</h2>
            <p>Máster en Seguridad de Tecnologías de la Información y Comunicaciones con especialidad en Redes y Sistemas. Profesional con amplia experiencia en el sector público y privado, comprometido con la seguridad de la información.</p>
        </section>

        <section id="experiencia" class="tab-content" style="display:none;">
            <h2>Experiencia Profesional</h2>
            <ul>
                <li><strong>Coordinador de Telemática</strong> - Municipio de Loja (2019-2022)</li>
                <li><strong>Docente Ocacional</strong> - Universidad de las Fuerzas Armadas ESPE (2023 - Presente)</li>
                <!-- Añadir más experiencias aquí -->
            </ul>
        </section>

        <section id="habilidades" class="tab-content" style="display:none;">
            <h2>Habilidades Técnicas</h2>
            <ul>
                <li>Evaluación de vulnerabilidades y pruebas de penetración</li>
                <li>Conocimiento ISO 27001</li>
                <li>Administración de redes y firewall Fortigate</li>
                <!-- Añadir más habilidades aquí -->
            </ul>
        </section>

        <section id="certificaciones" class="tab-content" style="display:none;">
            <h2>Certificaciones y Cursos</h2>
            <ul>
                <li>AWS Cloud Quest: Cloud Practitioner - Amazon Web Services</li>
                <li>OT Security Expert - OPSWAT Academy</li>
                <li>Ethical Hacking Certified Associate - CertJoin</li>
                <!-- Añadir más certificaciones aquí -->
            </ul>
        </section>

        <section id="contacto" class="tab-content" style="display:none;">
            <h2>Contacto</h2>
            <p>Puedes contactarme a través del siguiente formulario:</p>
            <form>
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Correo electrónico:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>

    <script src="scripts.js"></script>
</body>
</html>
