<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil Profesional</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .profile-header {
            text-align: center;
            margin-bottom: 20px;
        }
        .profile-header img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
        }
        .profile-header h1 {
            margin: 10px 0;
            font-size: 24px;
        }
        .section-title {
            font-size: 20px;
            border-bottom: 2px solid #000;
            padding-bottom: 5px;
            margin-bottom: 10px;
        }
        .skills, .education, .projects, .contact {
            margin-bottom: 20px;
        }
        .skills ul, .education ul, .projects ul, .contact ul {
            list-style: none;
            padding: 0;
        }
        .skills ul li, .education ul li, .projects ul li, .contact ul li {
            margin-bottom: 10px;
        }
        .project-card {
            display: inline-block;
            width: 45%;
            padding: 10px;
            margin: 5px;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.1);
        }
        .project-card h3 {
            margin-top: 0;
        }
        .social-links img {
            width: 24px;
            margin-right: 10px;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="profile-header">
        <img src="profile_picture.jpg" alt="Foto de perfil">
        <h1>Programador para Entornos Virtuales</h1>
    </div>
    <div class="skills">
        <h2 class="section-title">Habilidades</h2>
        <ul>
            <li>Lenguajes de programación: JavaScript, Python, HTML, CSS</li>
            <li>Cursos, Congresos y Seminarios: Curso avanzado de JavaScript, Congreso de IA</li>
            <li>Idiomas: Español, Inglés</li>
            <li>Data de interés: Machine Learning, Desarrollo de aplicaciones web</li>
            <li>Experiencia en proyectos: Desarrollo de aplicaciones para clientes, creación de APIs</li>
        </ul>
    </div>
    <div class="education">
        <h2 class="section-title">Formación Académica</h2>
        <ul>
            <li>Grado en Ingeniería Informática</li>
            <li>Certificación en Desarrollo Web</li>
        </ul>
    </div>
    <div class="projects">
        <h2 class="section-title">Proyectos</h2>
        <div class="project-card">
            <h3>Proyecto 1</h3>
            <p>Descripción del proyecto. Enlace al repositorio.</p>
        </div>
        <div class="project-card">
            <h3>Proyecto 2</h3>
            <p>Descripción del proyecto. Enlace al repositorio.</p>
        </div>
        <div class="project-card">
            <h3>Proyecto 3</h3>
            <p>Descripción del proyecto. Enlace al repositorio.</p>
        </div>
        <div class="project-card">
            <h3>Proyecto 4</h3>
            <p>Descripción del proyecto. Enlace al repositorio.</p>
        </div>
    </div>
    <div class="contact">
        <h2 class="section-title">Contacto</h2>
        <ul>
            <li>Email: tu_correo@example.com</li>
            <li>Teléfono: 123-456-7890</li>
        </ul>
        <div class="social-links">
            <a href="#"><img src="twitter_icon.png" alt="Twitter"></a>
            <a href="#"><img src="linkedin_icon.png" alt="LinkedIn"></a>
        </div>
    </div>
</div>

</body>
</html>
