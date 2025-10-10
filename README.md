<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portafolio | Daniel</title>
  <!-- Fuente e íconos -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2d9a6b77b.js" crossorigin="anonymous"></script>

  <style>
    :root {
      --bg-color: #0d1117;
      --card-color: #161b22;
      --text-color: #c9d1d9;
      --accent-color: #58a6ff;
      --hover-color: #1f6feb;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      text-align: center;
      margin-top: 50px;
    }

    header h1 {
      font-size: 2.5em;
      color: var(--accent-color);
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1em;
      opacity: 0.8;
    }

    .social-icons a {
      color: var(--text-color);
      margin: 10px;
      font-size: 1.4em;
      transition: color 0.3s;
    }

    .social-icons a:hover {
      color: var(--accent-color);
    }

    .section {
      background-color: var(--card-color);
      width: 90%;
      max-width: 900px;
      border-radius: 15px;
      padding: 30px;
      margin: 20px 0;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    }

    h2 {
      border-left: 4px solid var(--accent-color);
      padding-left: 10px;
      color: var(--accent-color);
      font-weight: 600;
    }

    .skills, .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    .skill, .project {
      background-color: #21262d;
      padding: 15px 20px;
      border-radius: 10px;
      flex: 1 1 250px;
      transition: transform 0.3s, background-color 0.3s;
    }

    .skill:hover, .project:hover {
      background-color: var(--hover-color);
      transform: translateY(-3px);
    }

    .project a {
      color: var(--text-color);
      text-decoration: none;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .footer {
      text-align: center;
      margin: 40px 0;
      font-size: 0.9em;
      opacity: 0.6;
    }
  </style>
</head>
<body>

  <header>
    <h1>👨‍💻 Daniel Pérez</h1>
    <p>Ingeniero en Sistemas | Desarrollador Backend | Analista de Datos</p>
    <div class="social-icons">
      <a href="https://github.com/tuusuario" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://linkedin.com/in/tuusuario" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:tucorreo@example.com"><i class="fas fa-envelope"></i></a>
    </div>
  </header>

  <section class="section">
    <h2>💼 Sobre mí</h2>
    <p>
      Soy un profesional apasionado por la tecnología y la automatización de procesos. 
      Me especializo en el análisis de datos, desarrollo de bots y gestión de información 
      en entornos empresariales. Busco aportar soluciones eficientes, escalables y seguras.
    </p>
  </section>

  <section class="section">
    <h2>🛠️ Habilidades</h2>
    <div class="skills">
      <div class="skill"><i class="fas fa-database"></i> SQL Server</div>
      <div class="skill"><i class="fab fa-python"></i> Python</div>
      <div class="skill"><i class="fab fa-git-alt"></i> Git / GitHub</div>
      <div class="skill"><i class="fas fa-network-wired"></i> Redes y Servidores</div>
      <div class="skill"><i class="fas fa-robot"></i> Automatización (Selenium / PyAutoGUI)</div>
    </div>
  </section>

  <section class="section">
    <h2>🚀 Proyectos Destacados</h2>
    <div class="projects">
      <div class="project">
        <a href="https://github.com/tuusuario/proyecto1" target="_blank">
          <span>Bot de Detección de Fraudes</span>
          <i class="fas fa-arrow-right"></i>
        </a>
      </div>
      <div class="project">
        <a href="https://github.com/tuusuario/proyecto2" target="_blank">
          <span>Automatización de Reportes FTP</span>
          <i class="fas fa-arrow-right"></i>
        </a>
      </div>
      <div class="project">
        <a href="https://github.com/tuusuario/proyecto3" target="_blank">
          <span>Gestor de Base de Datos Interno</span>
          <i class="fas fa-arrow-right"></i>
        </a>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>📫 Contacto</h2>
    <p>¿Quieres colaborar o saber más sobre mi trabajo? Contáctame:</p>
    <p><i class="fas fa-envelope"></i> tucorreo@example.com</p>
  </section>

  <div class="footer">
    <p>© 2025 Daniel Pérez — Desarrollado con ❤️ y código limpio.</p>
  </div>

</body>
</html>
