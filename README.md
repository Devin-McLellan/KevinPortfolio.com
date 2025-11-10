<!doctype html>
<html lang="sv">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Kevin McLellan – Data Engineer</title>
    <meta name="description" content="Portfolio och projekt av Kevin McLellan – Data Engineer & IT‑ingenjör." />
    <meta name="author" content="Kevin McLellan" />
    <meta property="og:title" content="Kevin McLellan – Data Engineer" />
    <meta property="og:description" content="Portfolio och projekt: data engineering, nätverk, Python, moln, statistik." />
    <meta property="og:type" content="website" />
    <meta property="og:image" content="/assets/preview.png" />
    <link rel="icon" href="/assets/favicon.ico" />
    <!-- Tailwind via CDN for simplicity on GitHub Pages -->
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="bg-zinc-50 text-zinc-900 antialiased">
    <!-- Header -->
    <header class="sticky top-0 z-40 bg-white/80 backdrop-blur border-b border-zinc-200">
      <div class="max-w-5xl mx-auto px-4 py-3 flex items-center justify-between">
        <a href="#" class="font-semibold tracking-tight">Kevin McLellan</a>
        <nav class="flex gap-4 text-sm">
          <a href="#projects" class="hover:underline">Projekt</a>
          <a href="#experience" class="hover:underline">Erfarenhet</a>
          <a href="#education" class="hover:underline">Utbildning</a>
          <a href="#skills" class="hover:underline">Kompetenser</a>
          <a href="#contact" class="hover:underline">Kontakt</a>
        </nav>
      </div>
    </header>

    <!-- Hero -->
    <section class="relative">
      <div class="max-w-5xl mx-auto px-4 py-16">
        <p class="text-sm uppercase tracking-widest text-zinc-500">#Data Engineer</p>
        <h1 class="mt-2 text-4xl md:text-5xl font-bold leading-tight">Bygger datapipelines som faktiskt rullar i produktion.</h1>
        <p class="mt-4 text-lg text-zinc-700 max-w-2xl">IT‑ingenjör med fokus på data engineering, statistik och moln. Bakgrund inom nätverk/säkerhet (CCNA), Python/SQL och automation (PowerShell). Gillar vältestade lösningar och tydlig dokumentation.</p>
        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#projects" class="px-4 py-2 rounded-xl bg-zinc-900 text-white">Se projekt</a>
          <a href="https://github.com/kevin" target="_blank" class="px-4 py-2 rounded-xl border border-zinc-300">GitHub</a>
          <a href="https://www.linkedin.com/in/kevin" target="_blank" class="px-4 py-2 rounded-xl border border-zinc-300">LinkedIn</a>
          <a href="/Kevin_CV.pdf" class="px-4 py-2 rounded-xl border border-zinc-300">Ladda ned CV</a>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="border-t border-zinc-200 bg-white">
      <div class="max-w-5xl mx-auto px-4 py-12">
        <h2 class="text-2xl font-semibold">Projekt</h2>
        <p class="mt-2 text-zinc-700">Urval av projekt och kurslabbar.</p>

        <div class="mt-6 grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
          <!-- Project Card Template -->
          <article class="group rounded-2xl border border-zinc-200 bg-white p-5 shadow-sm hover:shadow-md transition">
            <h3 class="font-semibold">ETL: Sensor → Lake → Warehouse</h3>
            <p class="mt-2 text-sm text-zinc-700">Bygger en daglig pipeline: rådata till Parquet i lake, dbt‑modeller till stjärnschema och dashboards.</p>
            <ul class="mt-3 text-xs text-zinc-600 list-disc ml-4">
              <li>Python, Pandas, DuckDB/BigQuery</li>
              <li>dbt, Airflow (lokalt), GitHub Actions</li>
              <li>Test: Great Expectations</li>
            </ul>
            <a class="mt-4 inline-block text-sm underline" href="https://github.com/kevin/etl-sensor-demo" target="_blank">Repo</a>
          </article>

          <article class="group rounded-2xl border border-zinc-200 bg-white p-5 shadow-sm hover:shadow-md transition">
            <h3 class="font-semibold">Nätverkslabbar (CCNA)</h3>
            <p class="mt-2 text-sm text-zinc-700">VLAN, trunkar, EtherChannel, STP, DHCP, NAT och OSPF i Packet Tracer/virtuella switchar.</p>
            <ul class="mt-3 text-xs text-zinc-600 list-disc ml-4">
              <li>Cisco IOS, Hyper‑V</li>
              <li>Konfig‑skript &amp; dokumentation</li>
            </ul>
            <a class="mt-4 inline-block text-sm underline" href="https://github.com/kevin/ccna-labs" target="_blank">Repo</a>
          </article>

          <article class="group rounded-2xl border border-zinc-200 bg-white p-5 shadow-sm hover:shadow-md transition">
            <h3 class="font-semibold">Statistikanalys i Python</h3>
            <p class="mt-2 text-sm text-zinc-700">Konfidensintervall, hypotesprövning, regression. Pedagogiska notebooks med svenska förklaringar.</p>
            <ul class="mt-3 text-xs text-zinc-600 list-disc ml-4">
              <li>NumPy, SciPy, Matplotlib</li>
              <li>Notebook‑till PDF export</li>
            </ul>
            <a class="mt-4 inline-block text-sm underline" href="https://github.com/kevin/statistik-notebooks" target="_blank">Repo</a>
          </article>
        </div>
      </div>
    </section>

    <!-- Experience -->
    <section id="experience" class="border-t border-zinc-200 bg-zinc-50">
      <div class="max-w-5xl mx-auto px-4 py-12">
        <h2 class="text-2xl font-semibold">Erfarenhet</h2>
        <ol class="mt-6 relative border-l border-zinc-200 ml-3">
          <li class="mb-8 ml-6">
            <div class="absolute -left-1.5 mt-1 h-3 w-3 rounded-full bg-zinc-900"></div>
            <h3 class="font-semibold">Store Manager – Kjell &amp; Company</h3>
            <p class="text-sm text-zinc-600">Ansvar för team, KPI:er och drift. Bemanning, onboarding och kundupplevelse.</p>
          </li>
          <li class="mb-8 ml-6">
            <div class="absolute -left-1.5 mt-1 h-3 w-3 rounded-full bg-zinc-900"></div>
            <h3 class="font-semibold">Sales Associate – Kjell &amp; Company</h3>
            <p class="text-sm text-zinc-600">Teknisk rådgivning, felsökning och merförsäljning. Utsågs ofta till “go‑to” för nätverksfrågor.</p>
          </li>
        </ol>
      </div>
    </section>

    <!-- Education -->
    <section id="education" class="border-t border-zinc-200 bg-white">
      <div class="max-w-5xl mx-auto px-4 py-12">
        <h2 class="text-2xl font-semibold">Utbildning</h2>
        <p class="mt-2">Högskolan i Borås – B.Sc. Computer Science (pågående)</p>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="border-t border-zinc-200 bg-zinc-50">
      <div class="max-w-5xl mx-auto px-4 py-12">
        <h2 class="text-2xl font-semibold">Kompetenser</h2>
        <div class="mt-4 grid sm:grid-cols-2 lg:grid-cols-3 gap-4 text-sm">
          <ul class="list-disc ml-5">
            <li>Python (Pandas, NumPy), SQL</li>
            <li>ETL/ELT, dbt, Airflow</li>
            <li>Data Modeling (stjärnschema, SCD)</li>
          </ul>
          <ul class="list-disc ml-5">
            <li>Moln: Azure/AWS (grunder)</li>
            <li>CI/CD: GitHub Actions</li>
            <li>Test &amp; observability: Great Expectations, logging</li>
          </ul>
          <ul class="list-disc ml-5">
            <li>Linux, Docker</li>
            <li>Nätverk: VLAN, STP, OSPF, NAT, DHCP</li>
            <li>Säkerhet: grundläggande härdning</li>
          </ul>
        </div>
        <div class="mt-6 text-sm text-zinc-700">
          <p><span class="font-medium">Cert:</span> CCNA (pågående).</p>
          <p class="mt-1"><span class="font-medium">Språk:</span> Svenska, Engelska.</p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="border-t border-zinc-200 bg-white">
      <div class="max-w-5xl mx-auto px-4 py-12">
        <h2 class="text-2xl font-semibold">Kontakt</h2>
        <p class="mt-2 text-zinc-700">Vill du bolla ett uppdrag, projekt eller idé? Hör av dig.</p>
        <div class="mt-4 text-sm">
          <p>E‑post: <a class="underline" href="mailto:kevin@kevinportfolio.com">kevin@kevinportfolio.com</a></p>
          <p>GitHub: <a class="underline" target="_blank" href="https://github.com/kevin">github.com/kevin</a></p>
          <p>LinkedIn: <a class="underline" target="_blank" href="https://www.linkedin.com/in/kevin">linkedin.com/in/kevin</a></p>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-zinc-200 bg-zinc-50">
      <div class="max-w-5xl mx-auto px-4 py-6 text-sm text-zinc-600 flex items-center justify-between">
        <p>© <span id="year"></span> Kevin McLellan</p>
        <p class="italic">“Ship small, ship often.”</p>
      </div>
    </footer>

    <script>
      document.getElementById('year').textContent = new Date().getFullYear();
    </script>
  </body>
</html>
