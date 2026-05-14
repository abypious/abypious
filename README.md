<!-- <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aby Pious — GitHub Profile</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500&family=Syne:wght@400;600;700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/dist/tabler-icons.min.css" />
  <style>
    *, *::before, *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Syne', sans-serif;
      background-color: #f5f5f3;
      color: #1a1a1a;
      padding: 2rem 1rem;
      min-height: 100vh;
    }

    .wrap {
      max-width: 760px;
      margin: 0 auto;
    }

    /* Hero */
    .hero {
      display: flex;
      align-items: center;
      gap: 1.5rem;
      margin-bottom: 1.5rem;
      padding: 1.5rem;
      border: 1px solid #e0e0db;
      border-radius: 14px;
      background: #ffffff;
    }

    .avatar {
      width: 72px;
      height: 72px;
      border-radius: 50%;
      background: linear-gradient(135deg, #1D9E75, #0F6E56);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 26px;
      font-weight: 700;
      color: #fff;
      flex-shrink: 0;
      letter-spacing: 1px;
    }

    .hero-info h1 {
      font-size: 22px;
      font-weight: 700;
      margin-bottom: 4px;
      color: #1a1a1a;
    }

    .hero-info p {
      font-size: 14px;
      color: #666;
      line-height: 1.6;
    }

    .tag-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 10px;
    }

    .tag {
      font-family: 'Fira Code', monospace;
      font-size: 11px;
      padding: 3px 10px;
      border-radius: 20px;
      background: #f0f0ec;
      border: 1px solid #ddd;
      color: #555;
    }

    /* Sections */
    .section {
      margin-bottom: 1.5rem;
    }

    .sec-title {
      font-size: 13px;
      font-weight: 600;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: #888;
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .sec-title i {
      font-size: 15px;
    }

    /* Bio card */
    .bio-card {
      padding: 1rem 1.25rem;
      border: 1px solid #e0e0db;
      border-radius: 14px;
      background: #ffffff;
    }

    .bio-row {
      display: flex;
      align-items: flex-start;
      gap: 10px;
      padding: 7px 0;
      font-size: 14px;
      color: #1a1a1a;
    }

    .bio-row i {
      font-size: 16px;
      color: #888;
      margin-top: 1px;
      flex-shrink: 0;
    }

    .bio-row a {
      color: #1D9E75;
      text-decoration: none;
    }

    .bio-row a:hover {
      text-decoration: underline;
    }

    .bio-divider {
      border: none;
      border-top: 1px solid #f0f0ec;
      margin: 0;
    }

    /* Stack grid */
    .stack-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(130px, 1fr));
      gap: 10px;
    }

    .stack-item {
      display: flex;
      align-items: center;
      gap: 8px;
      padding: 10px 12px;
      border: 1px solid #e0e0db;
      border-radius: 10px;
      background: #ffffff;
      font-size: 13px;
      font-weight: 500;
      color: #1a1a1a;
    }

    .stack-icon {
      width: 22px;
      height: 22px;
      border-radius: 4px;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }

    .stack-icon img {
      height: 14px;
      width: auto;
    }

    /* Stats grid */
    .stats-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
    }

    .stat-card {
      padding: 1rem;
      border: 1px solid #e0e0db;
      border-radius: 14px;
      background: #f5f5f3;
      text-align: center;
    }

    .stat-card img {
      width: 100%;
      border-radius: 6px;
      display: block;
    }

    /* Socials */
    .socials {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .soc-btn {
      display: inline-flex;
      align-items: center;
      gap: 7px;
      padding: 8px 14px;
      border: 1px solid #ddd;
      border-radius: 10px;
      background: #ffffff;
      font-size: 13px;
      font-weight: 500;
      color: #1a1a1a;
      text-decoration: none;
      font-family: 'Syne', sans-serif;
      transition: background 0.15s, border-color 0.15s;
    }

    .soc-btn:hover {
      background: #f0f0ec;
      border-color: #bbb;
    }

    .soc-btn i {
      font-size: 17px;
      color: #555;
    }

    /* Footer */
    .footer {
      margin-top: 2rem;
      padding-top: 1rem;
      border-top: 1px solid #e0e0db;
      font-size: 12px;
      color: #aaa;
      text-align: center;
      font-family: 'Fira Code', monospace;
    }

    /* Responsive */
    @media (max-width: 520px) {
      .hero {
        flex-direction: column;
        align-items: flex-start;
      }

      .stats-grid {
        grid-template-columns: 1fr;
      }

      .hero-info h1 {
        font-size: 19px;
      }
    }
  </style>
</head>
<body>

  <div class="wrap">

    <div class="hero">
      <div class="avatar">AP</div>
      <div class="hero-info">
        <h1>Aby Pious Vinoy</h1>
        <p>Android · Web · Software Developer<br>Learning Flutter &amp; React · Open to collaboration</p>
        <div class="tag-row">
          <span class="tag">Flutter</span>
          <span class="tag">Python</span>
          <span class="tag">Node.js</span>
          <span class="tag">Dart</span>
          <span class="tag">Firebase</span>
        </div>
      </div>
    </div>

    <!-- About -->
    <div class="section">
      <div class="sec-title">
        <i class="ti ti-user" aria-hidden="true"></i> About
      </div>
      <div class="bio-card">
        <div class="bio-row">
          <i class="ti ti-device-mobile" aria-hidden="true"></i>
          Building Android &amp; web apps
        </div>
        <hr class="bio-divider" />
        <div class="bio-row">
          <i class="ti ti-school" aria-hidden="true"></i>
          Currently learning Flutter &amp; React
        </div>
        <hr class="bio-divider" />
        <div class="bio-row">
          <i class="ti ti-handshake" aria-hidden="true"></i>
          Looking for help with Flutter projects
        </div>
        <hr class="bio-divider" />
        <div class="bio-row">
          <i class="ti ti-world" aria-hidden="true"></i>
          <a href="https://abypious.vercel.app/" target="_blank" rel="noopener">abypious.vercel.app</a>
        </div>
        <hr class="bio-divider" />
        <div class="bio-row">
          <i class="ti ti-mail" aria-hidden="true"></i>
          <a href="mailto:aby.pious.in@gmail.com">aby.pious.in@gmail.com</a>
        </div>
      </div>
    </div>

    <!-- Tech Stack -->
    <div class="section">
      <div class="sec-title">
        <i class="ti ti-code" aria-hidden="true"></i> Tech stack
      </div>
      <div class="stack-grid">
        <div class="stack-item">
          <div class="stack-icon" style="background:#E1F5EE;">
            <img src="https://img.shields.io/badge/-Python-3670A0?logo=python&logoColor=ffdd54" alt="Python" />
          </div>
          Python
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#E6F1FB;">
            <img src="https://img.shields.io/badge/-Dart-0175C2?logo=dart&logoColor=white" alt="Dart" />
          </div>
          Dart
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#E6F1FB;">
            <img src="https://img.shields.io/badge/-Flutter-02569B?logo=Flutter&logoColor=white" alt="Flutter" />
          </div>
          Flutter
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#FAEEDA;">
            <img src="https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5" />
          </div>
          HTML5
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#EAF3DE;">
            <img src="https://img.shields.io/badge/-Node.js-6DA55F?logo=node.js&logoColor=white" alt="Node.js" />
          </div>
          Node.js
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#FAEEDA;">
            <img src="https://img.shields.io/badge/-Firebase-039BE5?logo=firebase" alt="Firebase" />
          </div>
          Firebase
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#E6F1FB;">
            <img src="https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL" />
          </div>
          MySQL
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#EEEDFE;">
            <img src="https://img.shields.io/badge/-Figma-F24E1E?logo=figma&logoColor=white" alt="Figma" />
          </div>
          Figma
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#FCEBEB;">
            <img src="https://img.shields.io/badge/-Git-F05033?logo=git&logoColor=white" alt="Git" />
          </div>
          Git
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#FAEEDA;">
            <img src="https://img.shields.io/badge/-C%2B%2B-00599C?logo=c%2B%2B&logoColor=white" alt="C/C++" />
          </div>
          C / C++
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#F1EFE8;">
            <img src="https://img.shields.io/badge/-Flask-000?logo=flask&logoColor=white" alt="Flask" />
          </div>
          Flask
        </div>
        <div class="stack-item">
          <div class="stack-icon" style="background:#EEEDFE;">
            <img src="https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white" alt="Vite" />
          </div>
          Vite
        </div>
      </div>
    </div>

    <!-- GitHub Stats -->
    <div class="section">
      <div class="sec-title">
        <i class="ti ti-chart-bar" aria-hidden="true"></i> GitHub stats
      </div>
      <div class="stats-grid">
        <div class="stat-card">
          <img
            src="https://github-readme-stats.vercel.app/api?username=abypious&theme=dark&hide_border=true&include_all_commits=false&count_private=false"
            alt="GitHub Stats"
          />
        </div>
        <div class="stat-card">
          <img
            src="https://github-readme-stats.vercel.app/api/top-langs/?username=abypious&theme=dark&hide_border=true&layout=compact"
            alt="Top Languages"
          />
        </div>
      </div>
    </div>

    <!-- Connect -->
    <div class="section">
      <div class="sec-title">
        <i class="ti ti-share" aria-hidden="true"></i> Connect
      </div>
      <div class="socials">
        <a class="soc-btn" href="https://www.linkedin.com/in/aby-pious-b431312b4/" target="_blank" rel="noopener">
          <i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn
        </a>
        <a class="soc-btn" href="https://twitter.com/aby_pious" target="_blank" rel="noopener">
          <i class="ti ti-brand-twitter" aria-hidden="true"></i> Twitter / X
        </a>
        <a class="soc-btn" href="https://stackoverflow.com/users/19415712/aby-pious" target="_blank" rel="noopener">
          <i class="ti ti-brand-stackoverflow" aria-hidden="true"></i> Stack Overflow
        </a>
        <a class="soc-btn" href="https://instagram.com/mr.pious_" target="_blank" rel="noopener">
          <i class="ti ti-brand-instagram" aria-hidden="true"></i> Instagram
        </a>
        <a class="soc-btn" href="https://abypious.vercel.app/" target="_blank" rel="noopener">
          <i class="ti ti-world" aria-hidden="true"></i> Portfolio
        </a>
      </div>
    </div>

    <!-- Footer -->
    <div class="footer">© 2024 Aby Pious Vinoy · All rights reserved</div>

  </div>

</body>
</html> -->
