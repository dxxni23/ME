# ME

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48d5bfb3-0b43-422a-a212-617df0debd08" />
<HR>
<n>Español </n>
<hr>
<br>
<br>
- Estudiante de Grado Medio de Sistemas Microinformaticos y Redes (SMR).


<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>README — Estudiante de Informática</title>
  <meta name="description" content="README bonito en HTML para perfil de GitHub — Estudiante de Informática" />
  <style>
    :root{
      --bg:#0b0b0c;
      --card:#0f1113;
      --muted:#9aa4b2;
      --accent:#6ee7b7;
      --glass: rgba(255,255,255,0.03);
      --glass-2: rgba(255,255,255,0.02);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    html,body{height:100%;}
    body{
      margin:0;
      background:linear-gradient(180deg,var(--bg),#070708 120%);
      color:#e6eef6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:32px;
      display:flex;
      align-items:center;
      justify-content:center;
    }
    .container{
      width:980px;
      max-width:96vw;
      background:linear-gradient(180deg,var(--card),#0b0d0f);
      border-radius:18px;
      box-shadow:0 10px 30px rgba(2,6,23,0.7);
      overflow:hidden;
      border:1px solid rgba(255,255,255,0.03);
    }
    header{
      display:flex;
      gap:20px;
      padding:28px;
      align-items:center;
      border-bottom:1px solid var(--glass-2);
    }
    .avatar{
      flex:0 0 120px;
      height:120px;
      border-radius:16px;
      overflow:hidden;
      background:linear-gradient(135deg,#111318, #0b1220);
      display:flex;
      align-items:center;
      justify-content:center;
    }
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    .meta{flex:1}
    h1{margin:0;font-size:22px;letter-spacing:-0.3px}
    .role{color:var(--muted);margin-top:6px}
    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:var(--glass);padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted);}

    .content{display:grid;grid-template-columns:1fr 320px;gap:24px;padding:26px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);padding:18px;border-radius:12px;border:1px solid var(--glass);}
    .about p{color:var(--muted);line-height:1.6;margin:0}

    .skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .skill{background:transparent;padding:8px 10px;border-radius:10px;border:1px solid rgba(255,255,255,0.03);font-size:13px}

    .projects .grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;margin-top:12px}
    .proj{display:block;border-radius:10px;overflow:hidden;border:1px solid var(--glass-2);}
    .proj img{width:100%;height:120px;object-fit:cover;display:block}
    .proj .txt{padding:10px}
    .proj h4{margin:0;font-size:14px}
    .proj p{margin:6px 0 0;font-size:13px;color:var(--muted)}

    aside .contact{display:flex;flex-direction:column;gap:10px}
    .links a{display:inline-flex;align-items:center;gap:8px;padding:10px;border-radius:10px;text-decoration:none;color:inherit;border:1px solid var(--glass);}

    footer{padding:18px;border-top:1px solid var(--glass-2);text-align:center;color:var(--muted);font-size:13px}

    pre{background:#060607;padding:12px;border-radius:8px;overflow:auto;border:1px solid rgba(255,255,255,0.02);font-size:13px}

    /* responsive */
    @media (max-width:900px){
      .content{grid-template-columns:1fr}
      aside{order:2}
    }
  </style>
</head>
<body>
  <!--
    README HTML listo para usar en GitHub Pages o incrustar en README.md
    Reemplaza las imágenes por las tuyas subiéndolas al repositorio y cambiando las URLs.
  -->
  <div class="container">
    <header>
      <div class="avatar">
        <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Foto de perfil" />
      </div>
      <div class="meta">
        <h1>Hola — Soy [Tu Nombre]</h1>
        <div class="role">Estudiante de Ingeniería Informática · Desarrollador web · Aprendiz de DevOps</div>
        <div class="badges">
          <span class="badge">📚 Estudiante</span>
          <span class="badge">💻 JavaScript • Python</span>
          <span class="badge">⭐ Buscando prácticas</span>
        </div>
      </div>
      <div style="display:flex;flex-direction:column;gap:8px">
        <a class="badge" href="#contact">Contactar</a>
        <a class="badge" href="#projects">Proyectos</a>
      </div>
    </header>

    <div class="content">
      <main>
        <section class="card about">
          <h3>Sobre mí</h3>
          <p>Soy estudiante de Informática apasionado por el desarrollo de software y la tecnología. Me gusta aprender frameworks modernos, resolver problemas con código y colaborar en proyectos open source. Actualmente estudio en la universidad y trabajo en proyectos personales para mejorar mis habilidades.</p>

          <div class="skills">
            <div class="skill">JavaScript</div>
            <div class="skill">React</div>
            <div class="skill">Node.js</div>
            <div class="skill">Python</div>
            <div class="skill">SQL</div>
            <div class="skill">Git & GitHub</div>
          </div>
        </section>

        <section id="projects" class="card projects">
          <h3>Proyectos destacados</h3>
          <div class="grid">
            <a class="proj" href="#">
              <img src="https://images.unsplash.com/photo-1526378720302-63e1c4ef5b3a?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Captura proyecto 1">
              <div class="txt"><h4>Mi web personal</h4><p>Portfolio responsive creado con React y Tailwind.</p></div>
            </a>

            <a class="proj" href="#">
              <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Captura proyecto 2">
              <div class="txt"><h4>App de tareas</h4><p>Aplicación full-stack con autenticación y API REST.</p></div>
            </a>

            <a class="proj" href="#">
              <img src="https://images.unsplash.com/photo-1515879218367-8466d910aaa4?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Captura proyecto 3">
              <div class="txt"><h4>Bot de Discord</h4><p>Bot para automatizar tareas y moderación en servidores.</p></div>
            </a>

            <a class="proj" href="#">
              <img src="https://images.unsplash.com/photo-1517433456452-f9633a875f6f?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Captura proyecto 4">
              <div class="txt"><h4>Mini juego</h4><p>Juego HTML5 usando Canvas y lógica en JS.</p></div>
            </a>
          </div>
        </section>

        <section class="card code-sample" style="margin-top:16px">
          <h3>Snippet</h3>
          <pre><code>// Ejemplo: servidor simple en Node.js
const http = require('http');
const server = http.createServer((req,res)=>{
  res.writeHead(200,{'Content-Type':'text/plain'});
  res.end('Hola desde mi servidor Node!');
});
server.listen(3000, ()=> console.log('Server running on http://localhost:3000'));
</code></pre>
        </section>

      </main>

      <aside>
        <div class="card contact">
          <h3 id="contact">Contacto</h3>
          <div class="links">
            <a href="mailto:tuemail@example.com">✉️ Email — tuemail@example.com</a>
            <a href="https://github.com/tuusuario">🐙 GitHub — @tuusuario</a>
            <a href="https://www.linkedin.com/in/tuusuario">💼 LinkedIn</a>
          </div>

          <h4 style="margin-top:14px">Redes</h4>
          <div style="display:flex;gap:8px;margin-top:8px">
            <!-- small social SVG icons -->
            <a href="#" title="Twitter" style="display:inline-flex;padding:8px;border-radius:8px;border:1px solid var(--glass);">Twitter</a>
            <a href="#" title="YouTube" style="display:inline-flex;padding:8px;border-radius:8px;border:1px solid var(--glass);">YouTube</a>
          </div>

          <h4 style="margin-top:14px">Descargar CV</h4>
          <a class="links" href="#">📄 CV (PDF)</a>
        </div>

        <div class="card" style="margin-top:16px">
          <h3>Stats</h3>
          <p style="color:var(--muted);margin:0">Contribuciones recientes, proyectos abiertos y actividades académicas.</p>
          <div style="margin-top:12px"><img src="https://ghchart.rshah.org/yourgithubname" alt="GitHub chart" style="width:100%;border-radius:8px;border:1px solid var(--glass-2)"></div>
        </div>
      </aside>
    </div>

    <footer>
      Hecho con ❤️ — Estudiante de Informática.
    </footer>
  </div>
</body>
</html>
