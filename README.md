<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Haider Arshad — Full-Stack Developer</title>
  <meta name="description" content="Haider Arshad — Full-Stack Developer. Web & Mobile apps, MERN, Flutter, React Native, Django, AWS, Python, Java, SQL, MongoDB, Firebase." />
  <style>
    :root{
      --bg:#0f1724; --card:#111827; --muted:#94a3b8; --accent:#06b6d4; --glass: rgba(255,255,255,0.03);
      --gap:18px; --radius:14px; font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; background:linear-gradient(180deg,#071023 0%, #081226 60%); color:#e6eef6;
      -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; padding:32px;
    }
    .container{max-width:1100px;margin:0 auto;display:grid;grid-template-columns:1fr 350px;gap:28px;align-items:start}
    header{grid-column:1 / -1; display:flex; gap:20px; align-items:center}
    .avatar{width:96px;height:96px;border-radius:16px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:700;color:#021; font-size:28px}
    h1{margin:0;font-size:26px}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:15px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); padding:18px;border-radius:12px;box-shadow:0 6px 30px rgba(2,6,23,0.6); border:1px solid rgba(255,255,255,0.03)}
    .left .meta{display:flex;gap:12px;flex-wrap:wrap;margin-top:12px}
    .badge{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:999px;background:var(--glass);color:var(--muted);font-weight:600;font-size:13px}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-top:14px}
    .tech-grid{display:flex;flex-wrap:wrap;gap:10px;margin-top:10px}
    .tech-grid img{height:34px;border-radius:8px; background:#071028;padding:4px}
    .stats{display:flex;flex-direction:column;gap:12px}
    .project-list{display:grid;gap:12px;margin-top:12px}
    .project{padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.02)}
    .small{font-size:13px;color:var(--muted)}
    .right .right-col{position:sticky;top:28px}
    .socials{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
    .socials a{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:10px;background:rgba(255,255,255,0.02);text-decoration:none;color:#e6eef6;font-weight:600}
    .contrib-note{margin-top:10px;padding:10px;border-radius:8px;background:linear-gradient(90deg, rgba(255,255,255,0.012), rgba(255,255,255,0.01));color:var(--muted);font-size:13px}
    footer{grid-column:1 / -1;margin-top:18px;color:var(--muted);font-size:13px;text-align:center}
    @media (max-width:980px){.container{grid-template-columns:1fr; padding-bottom:60px} .right{order:2} .left{order:1}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">HA</div>
      <div>
        <h1>Haider Arshad</h1>
        <p class="lead">Full-Stack Developer — web & mobile. I design and build scalable, user-focused products using modern stacks (MERN, Flutter, React Native, Django, Node.js) with an emphasis on maintainability, performance and measurable outcomes.</p>
        <div class="meta" style="margin-top:12px">
          <span class="badge">📍 Pakistan</span>
          <span class="badge">🧭 Product-driven</span>
          <span class="badge">⚙️ System design & architecture</span>
        </div>
      </div>
    </header>

    <!-- Left column -->
    <main class="left">
      <section class="card">
        <h3 style="margin:0 0 6px 0">Professional Summary</h3>
        <div class="small">I build reliable, high-performance web and mobile applications, focusing on clean architecture, observable metrics, and polished user experiences. Strong background in front-end & back-end, cross-platform mobile, and cloud deployments.</div>

        <div class="grid" style="margin-top:16px">
          <div>
            <h4 style="margin:0 0 6px 0">Core Expertise</h4>
            <ul style="margin:0;padding-left:18px;color:var(--muted)">
              <li>Full-stack web development (MERN, Django, Node/Express)</li>
              <li>Mobile apps (React Native, Flutter)</li>
              <li>Databases & data pipelines (Postgres/SQL, MongoDB)</li>
              <li>Cloud & infra (AWS, CI/CD, Firebase)</li>
            </ul>
          </div>
          <div>
            <h4 style="margin:0 0 6px 0">Approach</h4>
            <div class="small">Ship small, iterate fast, measure impact. I prioritize code quality, automated tests, and observability so features stay maintainable at scale.</div>
          </div>
        </div>

        <div style="margin-top:14px">
          <h4 style="margin:0 0 8px 0">Technologies</h4>
          <div class="tech-grid">
            <!-- shields / logos (use shields.io or known icons) -->
            <img src="https://img.shields.io/badge/MERN-000000?style=for-the-badge&logo=react&logoColor=white" alt="MERN">
            <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react" alt="React Native">
            <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter" alt="Flutter">
            <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql" alt="SQL">
            <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb" alt="MongoDB">
            <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
            <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular" alt="Angular">
            <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js" alt="Node">
            <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express" alt="Express">
            <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django" alt="Django">
            <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java" alt="Java">
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python" alt="Python">
            <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws" alt="AWS">
          </div>
        </div>
      </section>

      <section class="card" style="margin-top:16px">
        <h3 style="margin:0 0 8px 0">Selected Projects</h3>
        <div class="project-list">
          <article class="project">
            <strong>TravelSync</strong> — Cross-platform travel planner with offline caching, route optimization, and real-time sync. <div class="small">Stack: Flutter, Django, Postgres, Redis, AWS</div>
          </article>

          <article class="project">
            <strong>E-Vital</strong> — Healthcare frontend with secure auth, RBAC, and polished UI components. <div class="small">Stack: React, Node/Express, MongoDB, Firebase</div>
          </article>

          <article class="project">
            <strong>Carpool Microservice</strong> — Ride matching, fare negotiation and driver app. <div class="small">Stack: Django, Postgres, Flutter, Google Maps</div>
          </article>
        </div>

        <div class="small" style="margin-top:10px">Add direct repository links below each project for better visibility (replace placeholders with actual repo URLs).</div>
      </section>

      <section class="card" style="margin-top:16px">
        <h3 style="margin:0 0 8px 0">Contributions & GitHub</h3>
        <div class="stats">
          <div style="display:flex;gap:12px;flex-wrap:wrap;align-items:center">
            <img src="https://github-profile-trophy.vercel.app/?username=haiderarshad&theme=radical&no-frame=true" alt="trophies" style="height:86px;border-radius:10px">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=haiderarshad&theme=dark&hide_border=true" alt="streak" style="height:86px;border-radius:10px">
          </div>

          <div class="contrib-note">
            <strong>Why contributions might not show:</strong> public contribution graphs and some stats widgets depend on the exact GitHub username and on visibility of repositories and commits. To ensure full visibility:
            <ul style="margin:6px 0 0 18px;color:var(--muted)">
              <li>Confirm your GitHub username is <code>haiderarshad</code> (or update the widgets to your real username).</li>
              <li>Enable `include_all_commits=true` for stat widgets if you want commit counts from all repos.</li>
              <li>Private repo contributions are only visible to you on GitHub — third-party widgets may not show them.</li>
            </ul>
          </div>
        </div>
      </section>
    </main>

    <!-- Right column -->
    <aside class="right">
      <div class="right-col card">
        <h3 style="margin:0 0 8px 0">Get in touch</h3>
        <div class="small">Open to freelance work, collaboration, and full-time opportunities.</div>

        <div class="socials">
          <a href="https://www.linkedin.com/in/haider-arshad-a06578317/" target="_blank">LinkedIn</a>
          <a href="https://www.instagram.com/haiderarshad022/" target="_blank">Instagram</a>
          <a href="mailto:haiderarshad@gmail.com">Email</a>
          <a href="https://github.com/haiderarshad" target="_blank">GitHub</a>
        </div>

        <hr style="border:none;height:1px;background:rgba(255,255,255,0.03);margin:14px 0;border-radius:6px">

        <h4 style="margin:0 0 8px 0">Profile widgets</h4>
        <div style="display:flex;flex-direction:column;gap:10px">
          <!-- GitHub stats images (these call external services) -->
          <img src="https://github-readme-stats.vercel.app/api?username=haiderarshad&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_title=true&layout=compact" alt="GitHub stats" style="width:100%;border-radius:8px">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=haiderarshad&layout=compact&theme=dark&hide_title=true&langs_count=6" alt="Top languages" style="width:100%;border-radius:8px">
        </div>

        <div style="margin-top:12px">
          <a href="https://github.com/haiderarshad" style="display:inline-block;padding:10px 12px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#7c3aed);text-decoration:none;color:#021;font-weight:700">View GitHub</a>
        </div>
      </div>
    </aside>

    <footer>
      Crafted with ♥ by Haider Arshad • Replace placeholder links (StackOverflow id, repos) with real URLs for full integration.
    </footer>
  </div>
</body>
</html>
