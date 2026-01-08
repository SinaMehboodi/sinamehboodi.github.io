# sinamehboodi.github.io


<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Sina Mehboodi — Data-oriented engineer: Python data analysis, R&D, automation, instrumentation." />
  <meta name="theme-color" content="#0b1220" />
  <title>Sina Mehboodi | Data-Oriented Engineer</title>

  <!-- Open Graph -->
  <meta property="og:title" content="Sina Mehboodi | Data-Oriented Engineer" />
  <meta property="og:description" content="Complex problem solving, Python-based data analysis, R&D environments, and automation workflows." />
  <meta property="og:type" content="website" />

  <!-- Favicon (inline) -->
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Cdefs%3E%3ClinearGradient id='g' x1='0' y1='0' x2='1' y2='1'%3E%3Cstop stop-color='%2366e3ff'/%3E%3Cstop offset='1' stop-color='%238a5cff'/%3E%3C/linearGradient%3E%3C/defs%3E%3Crect width='64' height='64' rx='14' fill='%230b1220'/%3E%3Cpath d='M18 40c6 7 22 7 28 0' stroke='url(%23g)' stroke-width='6' fill='none' stroke-linecap='round'/%3E%3Cpath d='M22 24h20' stroke='url(%23g)' stroke-width='6' stroke-linecap='round'/%3E%3C/svg%3E" />

  <style>
    :root{
      --bg: #0b1220;
      --panel: rgba(255,255,255,0.06);
      --panel2: rgba(255,255,255,0.08);
      --text: rgba(255,255,255,0.90);
      --muted: rgba(255,255,255,0.66);
      --muted2: rgba(255,255,255,0.55);
      --border: rgba(255,255,255,0.14);
      --shadow: 0 14px 55px rgba(0,0,0,0.45);
      --shadow2: 0 10px 24px rgba(0,0,0,0.35);
      --grad: linear-gradient(135deg, #66e3ff, #8a5cff 55%, #ff6bd6);
      --grad2: linear-gradient(135deg, rgba(102,227,255,.22), rgba(138,92,255,.18), rgba(255,107,214,.16));
      --ring: 0 0 0 4px rgba(102,227,255,0.18);
      --radius: 18px;
      --radius2: 26px;
      --max: 1080px;
      --mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
      --sans: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
    }

    /* Light mode (optional) */
    @media (prefers-color-scheme: light) {
      :root{
        --bg: #f7f8fb;
        --panel: rgba(0,0,0,0.04);
        --panel2: rgba(0,0,0,0.055);
        --text: rgba(0,0,0,0.88);
        --muted: rgba(0,0,0,0.62);
        --muted2: rgba(0,0,0,0.55);
        --border: rgba(0,0,0,0.10);
        --shadow: 0 18px 50px rgba(13,23,43,0.18);
        --shadow2: 0 10px 24px rgba(13,23,43,0.12);
        --grad2: linear-gradient(135deg, rgba(102,227,255,.20), rgba(138,92,255,.16), rgba(255,107,214,.12));
      }
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body{
      margin:0;
      font-family: var(--sans);
      color: var(--text);
      background: radial-gradient(1200px 600px at 12% 10%, rgba(102,227,255,0.18), transparent 55%),
                  radial-gradient(900px 520px at 80% 20%, rgba(138,92,255,0.18), transparent 55%),
                  radial-gradient(900px 520px at 60% 95%, rgba(255,107,214,0.14), transparent 60%),
                  var(--bg);
      line-height: 1.55;
    }
    a{ color: inherit; text-decoration: none; }
    a:hover{ text-decoration: underline; }
    .wrap{
      max-width: var(--max);
      margin: 0 auto;
      padding: 28px 18px 60px;
    }
    .topbar{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap: 14px;
      padding: 10px 2px 20px;
    }
    .brand{
      display:flex; align-items:center; gap: 12px;
    }
    .logo{
      width: 44px; height: 44px; border-radius: 14px;
      background: var(--grad2);
      border: 1px solid var(--border);
      box-shadow: var(--shadow2);
      position: relative;
      overflow: hidden;
    }
    .logo:before{
      content:"";
      position:absolute; inset: -40% -40%;
      background: var(--grad);
      filter: blur(18px);
      opacity: .55;
      transform: rotate(18deg);
    }
    .brand h1{
      font-size: 16px; margin: 0;
      letter-spacing: .2px;
    }
    .brand p{
      margin: 0;
      font-size: 13px;
      color: var(--muted);
      font-family: var(--mono);
    }
    .actions{
      display:flex; gap: 10px; flex-wrap: wrap;
      justify-content:flex-end;
    }
    .btn{
      display:inline-flex; align-items:center; gap: 10px;
      padding: 10px 12px;
      border-radius: 14px;
      border: 1px solid var(--border);
      background: var(--panel);
      box-shadow: var(--shadow2);
      transition: transform .12s ease, border-color .12s ease, background .12s ease;
      font-size: 13px;
      color: var(--text);
      white-space: nowrap;
    }
    .btn:hover{ transform: translateY(-1px); border-color: rgba(102,227,255,0.34); background: var(--panel2); text-decoration:none;}
    .btn:focus{ outline: none; box-shadow: var(--shadow2), var(--ring); }
    .badge{
      font-family: var(--mono);
      font-size: 12px;
      padding: 6px 10px;
      border-radius: 999px;
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
      color: var(--muted);
    }

    .hero{
      margin-top: 8px;
      border-radius: var(--radius2);
      border: 1px solid var(--border);
      background: linear-gradient(180deg, rgba(255,255,255,0.06), rgba(255,255,255,0.03));
      box-shadow: var(--shadow);
      overflow: hidden;
      position: relative;
    }
    .hero:before{
      content:"";
      position:absolute; inset: -30%;
      background: var(--grad);
      filter: blur(44px);
      opacity: .16;
    }
    .hero-inner{
      position: relative;
      padding: 26px 22px;
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap: 18px;
    }
    @media (max-width: 860px){
      .hero-inner{ grid-template-columns: 1fr; }
    }
    .title{
      margin: 0 0 8px;
      font-size: 34px;
      letter-spacing: -0.6px;
      line-height: 1.15;
    }
    .subtitle{
      margin: 0 0 14px;
      color: var(--muted);
      font-size: 15px;
      max-width: 66ch;
    }
    .chips{ display:flex; flex-wrap:wrap; gap: 8px; margin-top: 14px; }
    .chip{
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
      padding: 7px 10px;
      border-radius: 999px;
      font-size: 13px;
      color: var(--muted);
    }

    .card{
      border-radius: var(--radius);
      border: 1px solid var(--border);
      background: var(--panel);
      box-shadow: var(--shadow2);
      padding: 16px 16px;
    }
    .card h3{
      margin: 0 0 10px;
      font-size: 14px;
      letter-spacing: .3px;
      text-transform: uppercase;
      color: var(--muted);
    }
    .kv{
      display:grid;
      gap: 10px;
      font-size: 14px;
    }
    .kv div{ display:flex; justify-content:space-between; gap: 10px; }
    .kv span{ color: var(--muted); }
    .kv strong{ font-weight: 650; }

    .grid{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap: 14px;
      margin-top: 14px;
    }
    @media (max-width: 980px){
      .grid{ grid-template-columns: 1fr; }
    }

    .section{
      margin-top: 18px;
      border-radius: var(--radius2);
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.03);
      box-shadow: var(--shadow2);
      overflow: hidden;
    }
    .section-head{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap: 12px;
      padding: 14px 16px;
      border-bottom: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
    }
    .section-head h2{
      margin:0;
      font-size: 14px;
      letter-spacing: .3px;
      text-transform: uppercase;
      color: var(--muted);
    }
    .section-body{
      padding: 16px;
      display:grid;
      gap: 12px;
    }
    .item{
      padding: 14px;
      border-radius: var(--radius);
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
    }
    .item-top{
      display:flex;
      align-items:flex-start;
      justify-content:space-between;
      gap: 14px;
    }
    .item h3{
      margin: 0;
      font-size: 16px;
      letter-spacing: -0.2px;
    }
    .meta{
      color: var(--muted);
      font-size: 13px;
      margin-top: 4px;
    }
    .dates{
      font-family: var(--mono);
      font-size: 12px;
      color: var(--muted);
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
      padding: 6px 10px;
      border-radius: 999px;
      white-space: nowrap;
    }
    ul{
      margin: 10px 0 0 18px;
      color: var(--text);
    }
    li{ margin: 6px 0; color: var(--muted); }
    .two-col{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }
    @media (max-width: 820px){
      .two-col{ grid-template-columns: 1fr; }
    }
    .pill-list{
      display:flex; flex-wrap:wrap; gap: 8px;
    }
    .pill{
      padding: 7px 10px;
      border-radius: 999px;
      border: 1px solid var(--border);
      background: rgba(255,255,255,0.04);
      color: var(--muted);
      font-size: 13px;
    }

    .footer{
      margin-top: 18px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      flex-wrap:wrap;
      gap: 10px;
      color: var(--muted);
      font-size: 13px;
      padding: 0 4px;
    }
    .sr-only{
      position:absolute; width:1px; height:1px; padding:0; margin:-1px;
      overflow:hidden; clip:rect(0,0,0,0); border:0;
    }
  </style>
</head>

<body>
  <div class="wrap">
    <header class="topbar" aria-label="Top navigation">
      <div class="brand">
        <div class="logo" aria-hidden="true"></div>
        <div>
          <h1>Sina Mehboodi</h1>
          <p>Data-Oriented Engineer • Munich, Germany</p>
        </div>
      </div>

      <nav class="actions" aria-label="Quick actions">
        <a class="btn" href="mailto:sinamehboodi@gmail.com" aria-label="Email Sina">
          <span aria-hidden="true">✉️</span><span>Email</span>
        </a>
        <a class="btn" href="https://www.sinamehboodi.io" target="_blank" rel="noreferrer">
          <span aria-hidden="true">🌐</span><span>Website</span>
        </a>
        <!-- Replace links below with your real profiles -->
        <a class="btn" href="https://www.linkedin.com/in/Sina-Mehboodi" target="_blank" rel="noreferrer">
          <span aria-hidden="true">in</span><span>LinkedIn</span>
        </a>
        <a class="btn" href="https://github.com/SinaMehboodi" target="_blank" rel="noreferrer">
          <span aria-hidden="true">⌂</span><span>GitHub</span>
        </a>
        <span class="badge">Open to R&amp;D / Data / Engineering</span>
      </nav>
    </header>

    <section class="hero" aria-label="Intro">
      <div class="hero-inner">
        <div>
          <h2 class="title">Complex problem solving.<br/>Data analysis. R&amp;D execution.</h2>
          <p class="subtitle">
            Data-oriented engineer with 7+ years of experience in complex problem solving, Python-based data analysis,
            and R&amp;D environments. Skilled in transforming complex systems into reliable, automated analysis workflows.
            Proven ability to work independently and collaboratively within multidisciplinary teams. Seeking data-driven,
            R&amp;D, or engineering roles in industry.
          </p>

          <div class="chips" aria-label="Key strengths">
            <span class="chip">Python • Data Analysis</span>
            <span class="chip">Automation Workflows</span>
            <span class="chip">Scientific Instrumentation</span>
            <span class="chip">SQL Systems</span>
            <span class="chip">R&amp;D Execution</span>
          </div>
        </div>

        <aside class="card" aria-label="Contact and quick facts">
          <h3>Contact</h3>
          <div class="kv">
            <div><span>Email</span><strong><a href="mailto:sinamehboodi@gmail.com">sinamehboodi@gmail.com</a></strong></div>
            <div><span>Phone</span><strong><a href="tel:+4914751586184">+49 147 5158 6184</a></strong></div>
            <div><span>Location</span><strong>Munich, Germany</strong></div>
            <div><span>Site</span><strong><a href="https://www.sinamehboodi.io" target="_blank" rel="noreferrer">sinamehboodi.io</a></strong></div>
          </div>
          <div style="height:12px"></div>
          <h3>Languages</h3>
          <div class="pill-list" aria-label="Languages">
            <span class="pill">English — Advanced (C1)</span>
            <span class="pill">German — A2</span>
            <span class="pill">Persian — Native</span>
          </div>
        </aside>
      </div>
    </section>

    <div class="grid" aria-label="Main content">
      <section class="section" aria-label="Education">
        <div class="section-head">
          <h2>Education</h2>
          <span class="dates">2010–2026</span>
        </div>
        <div class="section-body">
          <article class="item">
            <div class="item-top">
              <div>
                <h3>Ph.D. in Physics — Technische Universität München (TUM)</h3>
                <div class="meta">Munich, Germany • Supervisor: Prof. Dr. Christian Back</div>
                <div class="meta">Surface Engineering in Chiral Magnetic Insulators; Control of Topological Spin Textures</div>
              </div>
              <div class="dates">2022–2026</div>
            </div>
          </article>

          <article class="item">
            <div class="item-top">
              <div>
                <h3>Doctoral Studies in Physics (Coursework Completed) — IASBS</h3>
                <div class="meta">Zanjan, Iran</div>
              </div>
              <div class="dates">2017–2018</div>
            </div>
          </article>

          <article class="item">
            <div class="item-top">
              <div>
                <h3>M.Sc. in Physics — IASBS</h3>
                <div class="meta">Zanjan, Iran • GPA: 17.29/20 (3rd in class)</div>
              </div>
              <div class="dates">2015–2017</div>
            </div>
          </article>

          <article class="item">
            <div class="item-top">
              <div>
                <h3>B.Sc. in Physics (Atomic &amp; Molecular) — Urmia University</h3>
                <div class="meta">Urmia, Iran</div>
              </div>
              <div class="dates">2010–2014</div>
            </div>
          </article>
        </div>
      </section>

      <section class="section" aria-label="Experience">
        <div class="section-head">
          <h2>Professional Experience</h2>
          <span class="dates">2018–2021</span>
        </div>
        <div class="section-body">
          <article class="item">
            <div class="item-top">
              <div>
                <h3>IT Technician — Sepid Surgery Day Clinic</h3>
                <div class="meta">Shiraz, Iran</div>
              </div>
              <div class="dates">2020–2021</div>
            </div>
            <ul>
              <li>Maintained and optimized SQL-based medical data systems, improving reliability and reducing data errors.</li>
              <li>Provided technical support to medical staff, improving workflow efficiency.</li>
            </ul>
          </article>

          <article class="item">
            <div class="item-top">
              <div>
                <h3>Software Technician — Tarh-o-Paradazesh-e-Hooshmand-e-Aria</h3>
                <div class="meta">Shiraz, Iran</div>
              </div>
              <div class="dates">2018–2020</div>
            </div>
            <ul>
              <li>Installed, configured, and maintained hospital information systems; delivered on-site support and user training.</li>
              <li>Diagnosed and resolved software, hardware, and network issues under time-critical conditions.</li>
            </ul>
          </article>
        </div>
      </section>
    </div>

    <section class="section" aria-label="Skills">
      <div class="section-head">
        <h2>Technical Skills</h2>
        <span class="dates">Keywords</span>
      </div>
      <div class="section-body two-col">
        <article class="item">
          <h3 style="margin:0 0 8px;">Programming &amp; Data Analysis</h3>
          <div class="pill-list">
            <span class="pill">Python</span>
            <span class="pill">SQL Server</span>
            <span class="pill">Mathematica</span>
            <span class="pill">JavaScript</span>
            <span class="pill">LabVIEW</span>
          </div>
        </article>

        <article class="item">
          <h3 style="margin:0 0 8px;">Experimental &amp; Instrumentation</h3>
          <div class="pill-list">
            <span class="pill">VNA</span>
            <span class="pill">Lock-in Amplifiers</span>
            <span class="pill">SEM</span>
            <span class="pill">Nanofabrication</span>
            <span class="pill">Cryogenic Systems</span>
            <span class="pill">Synchrotron</span>
            <span class="pill">Resonant X-ray Scattering</span>
          </div>
        </article>

        <article class="item">
          <h3 style="margin:0 0 8px;">IT &amp; Systems</h3>
          <div class="pill-list">
            <span class="pill">Linux</span>
            <span class="pill">Windows</span>
            <span class="pill">Network Setup</span>
            <span class="pill">Maintenance</span>
            <span class="pill">PC Assembly</span>
            <span class="pill">Troubleshooting</span>
          </div>
        </article>

        <article class="item">
          <h3 style="margin:0 0 8px;">Collaboration</h3>
          <div class="pill-list">
            <span class="pill">Independent Work</span>
            <span class="pill">Team Collaboration</span>
            <span class="pill">Technical Communication</span>
            <span class="pill">Hands-on Execution</span>
          </div>
        </article>
      </div>
    </section>

    <section class="section" aria-label="Leadership">
      <div class="section-head">
        <h2>Leadership &amp; Activities</h2>
        <span class="dates">2016–2025</span>
      </div>
      <div class="section-body">
        <article class="item">
          <div class="item-top">
            <div>
              <h3>Teaching &amp; Technical Experience — TUM</h3>
              <div class="meta">Germany</div>
            </div>
            <div class="dates">2017–2025</div>
          </div>
          <ul>
            <li>Assisted in teaching Ferromagnetic Resonance (FMR) and Condensed Matter Physics.</li>
            <li>Supported laboratory experiments and delivered hands-on instruction to bachelor’s and master’s students.</li>
          </ul>
        </article>

        <article class="item">
          <div class="item-top">
            <div>
              <h3>Co-founder &amp; Member — Science House of Zanjan &amp; Physics Scientific Association (PSA)</h3>
              <div class="meta">IASBS, Zanjan, Iran</div>
            </div>
            <div class="dates">2016–2018</div>
          </div>
          <ul>
            <li>Built physics demos to help high-school students explore scientific concepts.</li>
          </ul>
        </article>
      </div>
    </section>

    <section class="section" aria-label="Honors and Publications">
      <div class="section-head">
        <h2>Honors &amp; Publication</h2>
        <span class="dates">Highlights</span>
      </div>
      <div class="section-body two-col">
        <article class="item">
          <div class="item-top">
            <div>
              <h3>Honors</h3>
              <div class="meta">Selected academic performance highlights</div>
            </div>
          </div>
          <ul>
            <li>Top 5% — National B.Sc. entrance exam (2010) and M.Sc. entrance exam (2015).</li>
            <li>Rank 113 / ~6000 — National Physics Ph.D. entrance exam (2017).</li>
            <li>UNIPOSRIO (Brazil) — Unified physics graduate entrance exam score: 6.5/10 (2019).</li>
          </ul>
        </article>

        <article class="item">
          <div class="item-top">
            <div>
              <h3>Publication</h3>
              <div class="meta">Peer-reviewed</div>
            </div>
          </div>
          <ul>
            <li>
              S. Mehboodi et al., <em>Science and Technology of Advanced Materials</em>, 2025 (Published online: 06 Aug 2025) —
              “Observation of distorted tilted conical phase at the surface of a bulk chiral magnet with resonant elastic x-ray scattering.”
            </li>
          </ul>
        </article>
      </div>
    </section>

    <footer class="footer" aria-label="Footer">
      <div>© <span id="year"></span> Sina Mehboodi</div>
      <div style="font-family:var(--mono);">
        Munich, Germany • <a href="mailto:sinamehboodi@gmail.com">sinamehboodi@gmail.com</a> • <a href="https://www.sinamehboodi.io" target="_blank" rel="noreferrer">sinamehboodi.io</a>
      </div>
    </footer>
  </div>

  <script>
    // Tiny helper: current year
    document.getElementById("year").textContent = new Date().getFullYear();

    // Smooth scroll for internal anchors if you add them later
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener("click", e => {
        e.preventDefault();
        const el = document.querySelector(a.getAttribute("href"));
        if (el) el.scrollIntoView({ behavior: "smooth", block: "start" });
      });
    });
  </script>
</body>
</html>
