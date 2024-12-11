<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nakao Inc. | Servicios Tecnológicos</title>
  <style>
    /* Estilado Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Configuración global */
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #eef2f3, #8e44ad);
      color: #333;
      line-height: 1.6;
    }

    /* Encabezado Profesional */
    header {
      background: #004080;
      color: white;
      padding: 15px 0;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
    }

    header h1 {
      font-size: 2.8rem;
    }

    header p {
      font-size: 1.2rem;
      margin: 5px 0;
    }

    /* Barra de navegación */
    nav {
      background: #00264d;
      padding: 10px 0;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-size: 1rem;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #f4b400;
    }

    /* Contenedor Principal */
    .container {
      padding: 20px;
    }

    /* Estilado de tarjetas dinámicas */
    .services-container {
      display: flex;
      justify-content: space-around;
      gap: 15px;
      flex-wrap: wrap;
      padding: 10px;
    }

    .service-card {
      background: white;
      box-shadow: 0 3px 6px rgba(0, 0, 0, 0.2);
      padding: 20px;
      border-radius: 8px;
      width: 300px;
      text-align: center;
      transition: transform 0.2s ease;
    }

    .service-card:hover {
      transform: scale(1.1);
    }

    /* Sección WhatsApp */
    .whatsapp-contact {
      padding: 15px;
      background: #25d366;
      color: white;
      border: none;
      border-radius: 5px;
      text-align: center;
      display: inline-block;
      font-size: 1rem;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }

    .whatsapp-contact:hover {
      background-color: #128c7e;
    }

    /* Footer */
    footer {
      background: #004080;
      color: white;
      padding: 10px 0;
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>

<body>
  <!-- Encabezado -->
  <header>
    <h1>Nakao Inc.</h1>
    <p>Soluciones Tecnológicas para Empresas y Usuarios</p>
  </header>

  <!-- Barra de Navegación -->
  <nav>
    <a href="#services">Servicios</a>
  </nav>

  <!-- Sección Servicios -->
  <div class="container">
    <section class="services-container">
      <div class="service-card">
        <h3>💻 Instalación de Windows</h3>
        <p>Windows 10: <strong>Bs 250</strong></p>
        <p>Windows 11: <strong>Bs 250</strong></p>
      </div>
      <div class="service-card">
        <h3>🖥 Ensamblaje de PC</h3>
        <p>Asesoría de componentes: <strong>Bs 100</strong></p>
        <p>Montaje completo: <strong>Bs 300</strong></p>
      </div>
      <div class="service-card">
        <h3>🔧 Soporte Técnico</h3>
        <p>Diagnóstico de hardware: <strong>Bs 150</strong></p>
        <p>Reparación de software: <strong>Bs 200</strong></p>
      </div>
    </section>

    <!-- Sección WhatsApp -->
    <div style="text-align: center; margin: 20px 0;">
      <a class="whatsapp-contact" href="https://wa.me/582001656" target="_blank">Contáctanos por WhatsApp</a>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 Nakao Inc. | Todos los derechos reservados.</p>
  </footer>
</body>

</html>
