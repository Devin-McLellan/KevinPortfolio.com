<!doctype html>
<html lang="sv">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Kevin McLellan – Data Engineer</title>
  <meta name="description" content="Portfolio för Kevin McLellan – Data Engineer & IT‑ingenjör. Projekt, erfarenhet och kontakt.">
  <style>
    :root{
      --bg:#0b1020;--panel:#0f172a;--line:#1e293b;--text:#e5e7eb;--muted:#94a3b8;--accent:#38bdf8;--ok:#34d399;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,Arial}
    a{color:var(--accent);text-decoration:none}
    a:hover{text-decoration:underline}
    img{max-width:100%;height:auto;border-radius:10px}
    .wrap{max-width:1040px;margin:0 auto;padding:24px}
    .section{margin-top:28px;border:1px solid var(--line);background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.00));border-radius:16px}
    .section>header{display:flex;align-items:center;justify-content:space-between;padding:16px 18px;border-bottom:1px solid var(--line)}
    .section>div{padding:18px}
    h1,h2,h3{margin:0}
    h1{font-size:34px;line-height:1.2}
    h2{font-size:20px}
    h3{font-size:16px}
    p{margin:8px 0}
    .muted{color:var(--muted)}
    .topbar{position:sticky;top:0;z-index:10;background:rgba(11,16,32,.7);backdrop-filter:saturate(160%) blur(8px);border-bottom:1px solid var(--line)}
    .topbar .inner{max-width:1040px;margin:0 auto;padding:10px 24px;display:flex;gap:14px;align-items:center;justify-content:space-between}
    nav a{color:var(--muted);margin-left:14px}
    nav a:hover{color:var(--text)}
    .hero{display:grid;grid-template-columns:1.2fr .8fr;gap:22px;align-items:center}
    .badge{display:inline-flex;gap:8px;align-items:center;padding:6px 10px;border:1px solid var(--line);border-radius:999px;color:var(--muted)}
    .badge .dot{width:8px;height:8px;border-radius:50%;background:var(--ok);box-shadow:0 0 12px rgba(52,211,153,.6)}
    .cta{display:flex;flex-wrap:wrap;gap:10px;margin-top:14px}
    .btn{display:inline-block;padding:10px 14px;border-radius:10px;border:1px solid var(--line);background:#0f172a}
    .btn.primary{background:var(--accent);color:#00111a;border-color:transparent}
    .grid{display:grid;gap:14px}
    .grid.cols-3{grid-template-columns:repeat(3,minmax(0,1fr))}
    .grid.cols-2{grid-template-columns:repeat(2,minmax(0,1fr))}
    @media (max-width:900px){.hero{grid-template-columns:1fr}.grid.cols-3{grid-template-columns:1fr}.grid.cols-2{grid-template-columns:1fr}}
    .card{padding:14px;border:1px solid var(--line);border-radius:12px;background:var(--panel)}
    .card h3{font-weight:600}
    .meta{font-size:13px;color:var(--muted)}
    .list{padding-left:18px;margin:6px 0}
    footer{margin:28px auto 18px;max-width:1040px;color:var(--muted);border-top:1px solid var(--line);padding-top:12px;display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
  </style>
</head>
<body>
  <div class="topbar">
    <div class="inner">
      <strong>Kevin McLellan</strong>
      <nav>
        <a href="#projects">Projekt</a>
        <a href="#experience">Erfarenhet</a>
        <a href="#skills">Kompetenser</a>
        <a href="#contact">Kontakt</a>
      </nav>
    </div>
  </div>

  <div class="wrap">
    <section class="section" id="about">
      <div class="hero">
        <div>
          <span class="badge"><span class="dot"></span><span>#Data Engineer</span></span>
          <h1 style="margin-top:10px">Bygger robusta datapipelines – från rådata till beslutsstöd.</h1>
          <p class="muted">IT‑ingenjör med fokus på data engineering, statistik och moln. Praktisk bakgrund i nätverk/säkerhet (CCNA), Python/SQL och automation.</p>
          <div class="cta">
            <a class="btn primary" href="#projects">Se projekt</a>
            <a class="btn" href="https://github.com/kevin" target="_blank" rel="noopener">GitHub</a>
            <a class="btn" href="https://www.linkedin.com/in/kevin" target="_blank" rel="noopener">LinkedIn</a>
          </div>
        </div>
        <div>
          <img src="profile.jpg" alt="Porträtt av Kevin" onerror="this.style.display='none'">
        </div>
      </div>
    </section>

    <section class="section" id="projects">
      <header><h2>Projekt</h2><span class="meta">Urval av praktiska arbeten</span></header>
      <div>
        <div class="grid cols-3">
          <article class="card">
            <h3>ETL: Sensor → Lake → Warehouse</h3>
            <p class="muted">Daglig pipeline: rådata till Parquet, dbt‑modeller till stjärnschema och dashboard.</p>
            <ul class="list meta"><li>Python, Pandas, DuckDB/BigQuery</li><li>dbt, schemaläggning (cron/GitHub Actions)</li><li>Test: Great Expectations</li></ul>
            <p><a href="https://github.com/kevin/etl-sensor-demo" target="_blank" rel="noopener">Visa repo →</a></p>
          </article>
          <article class="card">
            <h3>Nätverkslabbar (CCNA)</h3>
            <p class="muted">VLAN, trunkar, EtherChannel, STP, DHCP, NAT och OSPF i Packet Tracer/virtuellt labb.</p>
            <p><a href="https://github.com/kevin/ccna-labs" target="_blank" rel="noopener">Visa repo →</a></p>
          </article>
          <article class="card">
            <h3>Statistikanalys i Python</h3>
            <p class="muted">Konfidensintervall, hypotesprövning och regression. Notebook‑exempel på svenska.</p>
            <p><a href="https://github.com/kevin/statistik-notebooks" target="_blank" rel="noopener">Visa repo →</a></p>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="experience">
      <header><h2>Erfarenhet & Utbildning</h2><span class="meta">Kortfattat</span></header>
      <div class="grid cols-2">
        <div>
          <div class="card">
            <h3>Store Manager – Kjell & Company</h3>
            <p class="meta">Team, KPI:er, drift, onboarding och kundupplevelse.</p>
          </div>
          <div class="card" style="margin-top:12px">
            <h3>Sales Associate – Kjell & Company</h3>
            <p class="meta">Teknisk rådgivning, felsökning och merförsäljning.</p>
          </div>
        </div>
        <div>
          <div class="card">
            <h3>Högskolan i Borås</h3>
            <p class="meta">B.Sc. in Computer Science (pågående)</p>
            <ul class="list meta"><li>Data Engineering, Databaser, Statistik</li><li>Nätverk & IT‑säkerhet (CCNA)</li><li>Python/SQL, Linux</li></ul>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="skills">
      <header><h2>Kompetenser</h2><span class="meta">Teknikstack och verktyg</span></header>
      <div class="grid cols-3">
        <div class="card"><h3>Data</h3><ul class="list"><li>Python (Pandas, NumPy), SQL</li><li>ETL/ELT, dbt</li><li>Datamodellering (stjärnschema)</li></ul></div>
        <div class="card"><h3>DevOps & Moln</h3><ul class="list"><li>Git/GitHub, GitHub Actions</li><li>Docker, Linux</li><li>Azure/AWS (grunder)</li></ul></div>
        <div class="card"><h3>Nätverk & Säkerhet</h3><ul class="list"><li>VLAN, STP, OSPF</li><li>NAT, DHCP</li><li>Grundläggande härdning</li></ul></div>
      </div>
      <div class="meta" style="margin-top:8px">Cert: CCNA (pågående) · Språk: Svenska, Engelska</div>
    </section>

    <section class="section" id="contact">
      <header><h2>Kontakt</h2><span class="meta">Låt oss bygga något</span></header>
      <div>
        <p class="muted">Öppen för praktik, extrajobb och frilansuppdrag.</p>
        <p>E‑post: <a href="mailto:duncan.mclellan96@gmail.com">duncan.mclellan96@gmail.com</a></p>
        <p>Telefon: <a href="tel:+46793405043">0793‑405043</a></p>
      </div>
    </section>
  </div>

  <footer>
    <span>© <span id="y"></span> Kevin McLellan</span>
    <span class="meta">KevinPortfolio.com</span>
  </footer>
  <script>document.getElementById('y').textContent=new Date().getFullYear();</script>
</body>
</html>
