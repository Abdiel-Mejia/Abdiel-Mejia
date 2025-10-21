<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Perfil • Full Stack Developer</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#7c3aed;--muted:#9aa4b2;--glass:rgba(255,255,255,0.04)}
    *{box-sizing:border-box;font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial}
    body{margin:0;background:linear-gradient(180deg,#071024 0%, #071a2b 50%, #0a1220 100%);color:#e6eef6;min-height:100vh;display:flex;align-items:center;justify-content:center;padding:32px}
    .wrap{width:100%;max-width:1100px}
    header{display:flex;gap:20px;align-items:center;margin-bottom:22px}
    .avatar{width:96px;height:96px;border-radius:18px;background:linear-gradient(135deg,var(--accent),#06b6d4);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;color:white;box-shadow:0 8px 30px rgba(12,17,26,0.6)}
    h1{margin:0;font-size:22px}
    p.lead{margin:4px 0 0;color:var(--muted)}
    .layout{display:grid;grid-template-columns:360px 1fr;gap:20px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);border-radius:14px;padding:18px;box-shadow:0 6px 24px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    .section-title{font-size:13px;color:var(--muted);text-transform:uppercase;letter-spacing:1px;margin-bottom:10px}
    .skills{display:flex;flex-direction:column;gap:10px}

    .skill-row{display:flex;align-items:center;gap:12px}
    .chip{background:var(--glass);padding:8px 12px;border-radius:999px;font-size:13px;color:#cfe6ff;border:1px solid rgba(255,255,255,0.03)}

    .bar{flex:1;height:10px;background:rgba(255,255,255,0.06);border-radius:999px;overflow:hidden;position:relative}
    .bar > i{position:absolute;left:0;top:0;bottom:0;border-radius:999px;background:linear-gradient(90deg,var(--accent),#06b6d4);width:0;transition:width 1s cubic-bezier(.2,.9,.3,1)}
    .percent{width:48px;text-align:right;font-size:13px;color:var(--muted)}

    .tech-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:8px}
    .tech{padding:10px;border-radius:10px;background:rgba(255,255,255,0.02);display:flex;align-items:center;gap:10px;font-size:14px}
    .pill{background:rgba(0,0,0,0.25);padding:8px 10px;border-radius:8px;border:1px solid rgba(255,255,255,0.02);font-weight:600}

    main .top{display:flex;gap:16px;align-items:center;justify-content:space-between}
    .cta{background:linear-gradient(90deg,var(--accent),#06b6d4);padding:10px 14px;border-radius:10px;font-weight:700;color:white;text-decoration:none}

    .tagline{color:var(--muted);font-size:13px}

    footer{margin-top:16px;color:var(--muted);font-size:13px}

    /* Visual accents */
    .ribbon{position:relative;padding:8px 12px;border-radius:999px;background:rgba(255,255,255,0.03);display:inline-flex;align-items:center;gap:8px}
    .glow{position:absolute;inset:-2px;background:linear-gradient(90deg, rgba(124,58,237,0.06), rgba(6,182,212,0.04));filter:blur(18px);border-radius:14px;z-index:-1}

    /* Responsive */
    @media (max-width:920px){.layout{grid-template-columns:1fr}.avatar{width:80px;height:80px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="avatar">AM</div>
      <div>
        <h1>Developer Full Stack • Java &amp; JavaScript</h1>
        <p class="lead">Apasionado por los desafíos, con enfoque en buenas prácticas, rendimiento y despliegue a producción.</p>
      </div>
      <div style="margin-left:auto;text-align:right">
        <div class="ribbon"><span class="pill">Open to work</span><span class="tagline">GitHub: Abdiel-Mejia</span></div>
      </div>
    </header>

    <div class="layout">
      <aside class="card">
        <div class="section-title">Habilidades principales</div>
        <div class="skills">
          <div class="skill-row"><div class="chip">TypeScript</div><div class="bar"><i style="width:82%"></i></div><div class="percent">82%</div></div>
          <div class="skill-row"><div class="chip">JavaScript</div><div class="bar"><i style="width:90%"></i></div><div class="percent">90%</div></div>
          <div class="skill-row"><div class="chip">Java &amp; Spring Boot</div><div class="bar"><i style="width:88%"></i></div><div class="percent">88%</div></div>
          <div class="skill-row"><div class="chip">React / Angular / Vue</div><div class="bar"><i style="width:80%"></i></div><div class="percent">80%</div></div>
          <div class="skill-row"><div class="chip">Node / NPM / Vite</div><div class="bar"><i style="width:76%"></i></div><div class="percent">76%</div></div>
          <div class="skill-row"><div class="chip">Bases de datos &amp; Queries</div><div class="bar"><i style="width:92%"></i></div><div class="percent">92%</div></div>
          <div class="skill-row"><div class="chip">CI / Deployment</div><div class="bar"><i style="width:74%"></i></div><div class="percent">74%</div></div>
          <div class="skill-row"><div class="chip">C#, C++</div><div class="bar"><i style="width:60%"></i></div><div class="percent">60%</div></div>
        </div>

        <hr style="margin:14px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">
        <div class="section-title">Herramientas &amp; Flujo</div>
        <div class="tech-grid">
          <div class="tech"><strong>GitHub</strong><span style="margin-left:auto">Repositorios y PRs</span></div>
          <div class="tech"><strong>Maven</strong><span style="margin-left:auto">Build Java</span></div>
          <div class="tech"><strong>Docker</strong><span style="margin-left:auto">(sugerido)</span></div>
          <div class="tech"><strong>Android Studio</strong><span style="margin-left:auto">Apps</span></div>
          <div class="tech"><strong>JWT</strong><span style="margin-left:auto">Auth</span></div>
          <div class="tech"><strong>CSV / Excel</strong><span style="margin-left:auto">Export / Import</span></div>
        </div>

        <hr style="margin:14px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">
        <div class="section-title">Arquitectura &amp; Metodologías</div>
        <div style="display:flex;flex-direction:column;gap:8px">
          <div class="tech">Model • Controller • Repository • Service</div>
          <div class="tech">RESTful APIs • CRUD</div>
          <div class="tech">SCRUM • Buenas prácticas • Refactor &amp; Recodificación</div>
        </div>
      </aside>

      <main>
        <div class="card">
          <div class="top">
            <div>
              <div class="section-title">Sobre mí</div>
              <p>Soy Full Stack Developer con fuerte base en Java y un stack moderno de frontend. Entrego código limpio, optimizo consultas y llevo proyectos a producción. Me interesa la arquitectura, rendimiento y escalabilidad.</p>
            </div>
            <div style="text-align:right">
              <a class="cta" href="#">Ver portafolio</a>
              <div style="font-size:12px;color:var(--muted);margin-top:8px">Activo en GitHub y despliegues a producción</div>
            </div>
          </div>

          <hr style="margin:16px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">

          <div class="section-title">Stack técnico</div>
          <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:12px">
            <span class="chip">HTML</span>
            <span class="chip">CSS / SCSS</span>
            <span class="chip">JavaScript</span>
            <span class="chip">TypeScript</span>
            <span class="chip">React</span>
            <span class="chip">Angular</span>
            <span class="chip">Vue</span>
            <span class="chip">Node</span>
            <span class="chip">Spring Boot</span>
            <span class="chip">Maven</span>
            <span class="chip">NPM</span>
            <span class="chip">JWT</span>
            <span class="chip">MySQL / SQL</span>
            <span class="chip">CSV / Excel</span>
            <span class="chip">C#</span>
            <span class="chip">C++</span>
            <span class="chip">Android Studio</span>
            <span class="chip">Vite</span>
            <span class="chip">GitHub</span>
          </div>

          <div class="section-title">Proyectos destacados</div>
          <ul style="color:var(--muted);line-height:1.6">
            <li>API REST con Spring Boot y SQL optimizada para consultas rápidas y migraciones de BD.</li>
            <li>Frontend SPA en React/Angular con autenticación JWT y despliegue a producción.</li>
            <li>Automatización de generación de Excel/CSV y procesos ETL para migración de datos.</li>
          </ul>

          <footer>
            ¿Quieres que agregue más secciones (experiencia, certificaciones, ejemplos de código)?
          </footer>
        </div>
      </main>
    </div>
  </div>
  <script>
    // Animación simple: al cargar establecer el ancho de las barras (ya vienen en style inline)
    document.addEventListener('DOMContentLoaded', ()=>{
      const bars = document.querySelectorAll('.bar > i');
      bars.forEach(b=>{const w = b.style.width || '60%'; setTimeout(()=> b.style.width = w, 50)});
    });
  </script>
</body>
</html>
