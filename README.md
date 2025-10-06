<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>README — Miguel Ángel Vargas</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --accent:#3b82f6;
      --muted:#94a3b8;
      --glass: rgba(255,255,255,0.04);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      background: linear-gradient(180deg,#071029 0%, #071a2a 60%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
    }
    .wrap{max-width:900px;margin:36px auto;padding:28px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:12px;box-shadow:0 10px 30px rgba(2,6,23,0.6);}
    header{display:flex;align-items:center;gap:16px}
    .avatar{width:96px;height:96px;border-radius:16px;background:linear-gradient(135deg,var(--accent),#2563eb);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:28px;color:white}
    h1{margin:0;font-size:22px}
    .lead{color:var(--muted);margin-top:6px;font-size:14px}
    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:var(--glass);padding:6px 10px;border-radius:999px;color:var(--muted);font-weight:600;font-size:13px;border:1px solid rgba(255,255,255,0.03)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:18px}
    .card{background:rgba(255,255,255,0.02);padding:14px;border-radius:10px;border:1px solid rgba(255,255,255,0.03)}
    h2{margin:0 0 8px 0;color:#dbeafe;font-size:15px}
    p{margin:0;color:var(--muted);line-height:1.4}
    ul{margin:8px 0 0 18px;color:var(--muted)}
    li{margin-bottom:6px}
    .skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
    .skill{background:linear-gradient(90deg, rgba(59,130,246,0.12), rgba(37,99,235,0.06));padding:6px 8px;border-radius:8px;color:#cfe8ff;font-weight:700;font-size:13px;border:1px solid rgba(59,130,246,0.12)}
    .projects a{display:block;color:#bfdbfe;margin-bottom:8px;text-decoration:none;font-weight:700}
    .cta{display:flex;gap:10px;margin-top:12px}
    .btn{background:var(--accent);color:#04263a;padding:8px 12px;border-radius:8px;font-weight:700;text-decoration:none}
    .muted-tiny{font-size:12px;color:var(--muted);margin-top:8px}
    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}
    @media (max-width:880px){.grid{grid-template-columns:1fr;}.avatar{width:80px;height:80px;font-size:24px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">MA</div>
      <div>
        <h1>Miguel Ángel Vargas S.</h1>
        <div class="lead">Desarrollador Full Stack | Técnico en Sistemas — React · Node.js · PHP · Python</div>
        <div class="badges">
          <div class="badge">Open to: Desarrollo web • Soporte • Análisis de datos</div>
          <div class="badge">Ubicación: Medellín, Colombia</div>
          <div class="badge">Contacto: miguelaglvs@gmail.com</div>
        </div>
      </div>
    </header>

    <div class="grid">
      <div>
        <div class="card">
          <h2>Sobre mí</h2>
          <p>Soy desarrollador Full Stack con experiencia práctica en creación y mantenimiento de aplicaciones web. Me especializo en construir <strong>REST APIs</strong>, interfaces frontend eficientes y soluciones backend escalables. Mi trabajo combina buenas prácticas de programación, seguridad (JWT), y una visión orientada al usuario gracias a mi experiencia en soporte técnico.</p>
          <div class="muted-tiny">Busco roles en desarrollo web (frontend/backend) y posiciones que valoren experiencia con usuarios.</div>
          <div class="cta">
            <a class="btn" href="mailto:miguelaglvs@gmail.com">Contactarme</a>
            <a class="btn" href="https://github.com/MiguelAglVs" target="_blank">Ver proyectos</a>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Proyectos destacados</h2>
          <div class="projects">
            <a href="#">Sindis — App web (React / Node.js)</a>
            <a href="#">YourInk — Tienda online (PHP / MySQL)</a>
            <a href="#">Sistema de Gestión Odontológica (Python / SQLite)</a>
            <a href="#">ControlStock — Inventarios (Java)</a>
          </div>
          <div class="muted-tiny">Añade enlaces directos a repositorios o demos para aumentar credibilidad.</div>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Trayectoria profesional</h2>
          <ul>
            <li><strong>Sodexo</strong> — Analista de Datos (Abr 2024 – Sep 2024)</li>
            <li><strong>Misioneros Urbanos</strong> — Desarrollador Web (Nov 2023 – May 2024)</li>
          </ul>
        </div>
      </div>

      <aside class="side">
        <div class="card">
          <h2>Habilidades</h2>
          <div class="skills">
            <div class="skill">React</div>
            <div class="skill">Node.js</div>
            <div class="skill">PHP</div>
            <div class="skill">Python</div>
            <div class="skill">REST API</div>
            <div class="skill">MySQL</div>
            <div class="skill">PostgreSQL</div>
            <div class="skill">Oracle</div>
            <div class="skill">SQLite</div>
            <div class="skill">Git</div>
            <div class="skill">JWT</div>
            <div class="skill">Power BI</div>
            <div class="skill">Scrum</div>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h2>Conéctate</h2>
          <ul>
            <li><a href="mailto:miguelaglvs@gmail.com">miguelaglvs@gmail.com</a></li>
            <li><a href="https://github.com/MiguelAglVs" target="_blank">github.com/MiguelAglVs</a></li>
            <li><a href="https://www.linkedin.com/in/miguel-vargass" target="_blank">linkedin.com/in/miguel-vargass</a></li>
          </ul>
        </div>
      </aside>
    </div>
  </div>
</body>
</html>
