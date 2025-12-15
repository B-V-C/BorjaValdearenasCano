<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Borja Valdearenas Cano — CV</title>
  <link rel="stylesheet" href="borja.css" />
:root{
  --accent:#2b6ea3;
  --muted:#666;
  --bg:#f8fafc;
  --paper:#ffffff;
  --sidebar:#eef6fb;
  --maxw:980px;
  --radius:8px;
}

*{box-sizing:border-box}
body{
  font-family: -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
  background:var(--bg);
  color:#222;
  margin:20px;
  -webkit-font-smoothing:antialiased;
}

.container{
  max-width:var(--maxw);
  margin:0 auto;
  display:grid;
  grid-template-columns:280px 1fr;
  gap:22px;
  align-items:start;
}

/* Sidebar */
.sidebar{
  background:var(--sidebar);
  padding:20px;
  border-radius:var(--radius);
  box-shadow:0 2px 6px rgba(15,23,42,0.05);
}
.profile h1{
  font-size:26px;
  margin:0 0 6px 0;
  line-height:1.05;
}
.profile .surname{font-weight:600}
.meta{color:var(--muted);font-size:13px;margin-top:6px}

/* Sections */
.sidebar section{margin-top:18px}
.sidebar h2{
  margin:0 0 8px 0;
  font-size:14px;
  color:var(--accent);
  letter-spacing:0.6px;
}
.sidebar ul{padding-left:18px;margin:0}
.sidebar table{width:100%;font-size:13px;color:var(--muted)}

/* Main content */
.content{
  background:var(--paper);
  padding:26px;
  border-radius:var(--radius);
  box-shadow:0 2px 10px rgba(11,20,40,0.04);
}
.content h2{
  color:var(--accent);
  margin-top:0;
  font-size:18px;
}
.job{margin-bottom:16px;border-left:3px solid transparent;padding-left:12px}
.job h3{margin:6px 0;font-size:16px}
.period{color:var(--muted);font-size:13px;margin-bottom:8px}
.job ul{margin:0;padding-left:18px}

/* Responsive */
@media (max-width:880px){
  .container{grid-template-columns:1fr; padding:12px}
  .sidebar{order:2}
  .content{order:1}
}
.profile-photo {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  object-fit: cover;
  display: block;
  margin: 0 auto 12px auto;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
</head>
<body>
  <div class="container">
    <aside class="sidebar">
      <div class="profile">
        <img src="borja.jpg" alt="Foto de Borja Valdearenas Cano" class="profile-photo" />
        <h1>Borja<br/><span class="surname">Valdearenas Cano</span></h1>
        <p class="meta">Fecha Nacimiento: 29/11/1991 <br>
          Nacionalidad: Española</p>
      </div>

      <section class="contact">
        <h2>Contacto</h2>
        <p>Email: <a href="mailto:bvc91c@gmail.com">bvc91c@gmail.com</a></p>
        <p>Móvil: (+34) 601 263 365</p>
        <p>Dirección: Calle La Malaha, edificio 9, 2A, 18006, Granada, España</p>
      </section>

      <section class="skills">
        <h2>Competencias</h2>
        <ul>
          <li>Paquete OFFICEPLUS</li>
          <li>Mantenimiento de software y hardware</li>
          <li>Administración de redes wifi y recursos compartidos</li>
          <li>Máquinas virtuales</li>
        </ul>
      </section>

      <section class="languages">
        <h2>Idiomas</h2>
        <table>
          <tr><td>Español</td><td>Nativo</td></tr>
          <tr><td>Inglés</td><td>B1 (listening/reading) A2 (oral)</td></tr>
        </table>
      </section>

      <section class="hobbies">
        <h2>Aficiones</h2>
        <ul>
          <li>Natación</li>
          <li>Leer (novela negra y libros de informática)</li>
          <li>Senderismo</li>
        </ul>
      </section>
    </aside>

    <main class="content">
      <section class="summary">
        <h2>Sobre mí</h2>
        <p>Soy técnico en Sistemas Microinformáticos y Redes, con experiencia en mantenimiento, soporte técnico y atención al usuario. Me apasiona el mundo de la informática y disfruto resolviendo problemas, optimizando sistemas y aprendiendo nuevas tecnologías.

Actualmente estoy ampliando mi formación estudiando Desarrollo Web, con el objetivo de orientar mi carrera hacia la creación de aplicaciones y sitios web modernos, funcionales y seguros.

Me considero una persona responsable, organizada y con buena capacidad de trabajo en equipo. Mi meta es seguir creciendo en el ámbito tecnológico, combinando mis conocimientos en sistemas con las habilidades de programación y desarrollo web para ofrecer soluciones completas y de calidad.</p>
      </section>

      <section class="work">
        <h2>Experiencia laboral</h2>

        <article class="job">
          <h3>Hotel Eurostars Washington Irving 5* — Camarero</h3>
          <p class="period">05/05/2016 — Actual</p>
          <ul>
            <li>Servicio de sala y terraza.</li>
            <li>Uso de PDA.</li>
            <li>Manejo en TPV.</li>
            <li>Recepción de bebidas.</li>
            <li>Organización y limpieza.</li>
            <li>Responsable de sala.</li>
          </ul>
        </article>

        <article class="job">
          <h3>Hotel Golden Taurus Park Resort 4* — Camarero</h3>
          <p class="period">10/06/2015 — 10/10/2015</p>
          <ul>
            <li>Servicio de sala y terraza.</li>
            <li>Uso de PDA.</li>
            <li>Manejo en TPV.</li>
            <li>Organización y limpieza.</li>
          </ul>
        </article>

        <article class="job">
          <h3>Hotel Fontecruz — Camarero</h3>
          <p class="period">02/02/2015 — 11/05/2015</p>
          <ul>
            <li>Servicio de sala y terraza.</li>
            <li>Uso de PDA.</li>
            <li>Manejo en TPV.</li>
            <li>Recepción de bebidas.</li>
            <li>Organización y limpieza.</li>
          </ul>
        </article>

        <article class="job">
          <h3>Foster Hollywood — Camarero</h3>
          <p class="period">16/09/2014 — 15/01/2015</p>
          <ul>
            <li>Servicio de sala y terraza.</li>
            <li>Uso de PDA.</li>
            <li>Manejo en TPV.</li>
            <li>Organización y limpieza.</li>
          </ul>
        </article>

        <article class="job">
          <h3>Bar La Esparraguera — Camarero</h3>
          <p class="period">06/05/2013 — 16/10/2013</p>
          <ul>
            <li>Servicio de sala y terraza.</li>
            <li>Uso de PDA.</li>
            <li>Manejo en TPV.</li>
            <li>Recepción de bebidas.</li>
            <li>Organización y limpieza.</li>
            <li>Responsable de sala.</li>
          </ul>
        </article>

        <article class="job">
          <h3>Universidad de Granada — Prácticas Técnico Informático</h3>
          <p class="period">10/03/2024 — 10/06/2024</p>
          <ul>
            <li>Mantenimiento preventivo y correctivo de equipos y redes.</li>
            <li>Soporte técnico presencial y remoto a usuarios.</li>
            <li>Instalación de sistemas operativos, software y periféricos.</li>
            <li>Configuración de redes locales y copias de seguridad.</li>
            <li>Control de seguridad informática y actualización de sistemas.</li>
          </ul>
        </article>

        <article class="job">
          <h3>PeraStore S.L — Prácticas Técnico Informático</h3>
          <p class="period">15/01/2025 — 15/06/2025</p>
          <ul>
            <li>Mantenimiento preventivo y correctivo de equipos y redes.</li>
            <li>Soporte técnico presencial y remoto a usuarios.</li>
            <li>Instalación de sistemas operativos, software y periféricos.</li>
            <li>Configuración de redes locales y copias de seguridad.</li>
            <li>Control de seguridad informática y actualización de sistemas.</li>
          </ul>
        </article>

      </section>

      <section class="education">
        <h2>Educación y formación</h2>
        <p><strong>Técnico en Sistemas Microinformáticos y Redes</strong><br/>I.E.S Zaidin Vergeles — Inicio: 15/09/2023 Fin: 21/06/2025.</p>
        <p><strong>Educación Secundaria Obligatoria</strong><br/>I.E.S Sagrado Corazón — Inicio: 15/09/2003 Fin: 21/06/2007.</p>
      </section>
    </main>
  </div>
</body>
</html>
