<!-- 🎨 Colorful, Typing Effect README.md – Copy & Paste Me! -->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Lawkey Marvelous — Developer Readme Preview</title>
  <style>
    :root{
      --red: #ff2d2d;
      --black: #000000;
      --green: #00ff88;
      --accent: #4facfe;
      --muted: rgba(255,255,255,0.92);
      --card-bg: rgba(255,255,255,0.04);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    body{
      margin:0;
      padding:32px;
      background: linear-gradient(90deg, var(--red) 0%, var(--black) 50%, var(--green) 100%);
      color:var(--muted);
      min-height:100vh;
      box-sizing:border-box;
    }

    .container{
      max-width:900px;
      margin:0 auto;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), transparent);
      border-radius:12px;
      padding:28px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.45);
    }

    .heading{
      display:flex;
      align-items:center;
      gap:16px;
      margin-bottom:6px;
    }

    .logo {
      width:56px;
      height:56px;
      display:inline-flex;
      align-items:center;
      justify-content:center;
      border-radius:12px;
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(255,255,255,0.06);
    }

    h1{
      margin:0;
      font-size:1.6rem;
      line-height:1;
      color:var(--muted);
    }

    .subtitle {
      margin:6px 0 18px;
      font-size:1.05rem;
      color: rgba(255,255,255,0.85);
    }

    /* Typing effect */
    #typewriter{
      font-family: "Courier New", Courier, monospace;
      font-size:1.15rem;
      white-space:pre;
      display:inline-block;
      border-right:2px solid rgba(255,255,255,0.7);
      padding-right:6px;
      min-height:1.3em;
    }

    /* color-change animation for the name */
    .gradient-text{
      display:inline-block;
      background: linear-gradient(90deg, var(--red), var(--accent), var(--green));
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      font-weight:700;
      animation: hueShift 6s infinite linear;
    }

    @keyframes hueShift {
      0% { filter: hue-rotate(0deg); }
      50% { filter: hue-rotate(120deg); }
      100% { filter: hue-rotate(360deg); }
    }

    .grid{
      display:flex;
      gap:14px;
      flex-wrap:wrap;
      margin:18px 0;
    }

    .card{
      flex:1 1 240px;
      background: var(--card-bg);
      padding:14px;
      border-radius:10px;
      min-width:200px;
      border: 1px solid rgba(255,255,255,0.04);
    }

    .card h3{ margin:0 0 8px; color:var(--muted); }
    .card p{ margin:0; color: rgba(255,255,255,0.85); font-size:0.95rem; }

    .badges{
      display:flex;
      gap:8px;
      flex-wrap:wrap;
      margin:12px 0;
    }

    .badge{
      padding:6px 10px;
      border-radius:999px;
      font-weight:700;
      font-size:0.85rem;
      color:#fff;
    }
    .badge.react{ background:#61dafb; color:#052026; }
    .badge.node{ background:#83cd29; color:#042000; }
    .badge.tailwind{ background:#38bdf8; color:#032735; }
    .badge.python{ background:#ffd34d; color:#2b1e00; }
    .links{ margin-top:16px; display:flex; gap:10px; flex-wrap:wrap; }

    .btn{
      display:inline-block;
      padding:10px 14px;
      border-radius:8px;
      text-decoration:none;
      font-weight:700;
      color:var(--muted);
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(255,255,255,0.06);
    }

    footer{
      margin-top:20px;
      font-size:0.9rem;
      color:rgba(255,255,255,0.75);
      text-align:center;
    }

    a.inline-link{ color:var(--accent); text-decoration:underline; }

    @media (max-width:640px){
      .heading{ flex-direction:column; align-items:flex-start; gap:8px; }
      .grid{ flex-direction:column; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="heading">
      <div class="logo" aria-hidden="true">
        <!-- small goat-ish SVG icon -->
        <svg width="36" height="36" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
          <circle cx="12" cy="12" r="10" fill="white" opacity="0.05"/>
          <path d="M6 15c1.5-3 4-5 6-5s4.5 2 6 5" stroke="white" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M9 9c.6-1 1.6-2 3-2s2.4 1 3 2" stroke="white" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>

      <div>
        <h1><span class="gradient-text">Lawkey Marvelous</span> <small style="font-weight:600; font-size:0.9rem; color:rgba(255,255,255,0.85)">— Web Developer</small></h1>
        <p class="subtitle">Web Developer | Problem Solver | Coffee Lover ☕</p>
      </div>
    </div>

    <div id="typewriter" aria-live="polite"></div>

    <div class="grid">
      <div class="card">
        <h3 style="color:#ffdede">Featured Project</h3>
        <p>GoatBot — an automation & chatbot project. Built with Node.js and a modular command system.</p>
        <div class="links">
          <a class="btn" href="https://github.com/Dev-Lawk3y/automatic-giggle" target="_blank" rel="noopener">Repository</a>
          <a class="btn" href="https://example.com" target="_blank" rel="noopener">View Live</a>
        </div>
      </div>

      <div class="card">
        <h3 style="color:#ffdede">About Me</h3>
        <p>I build reliable web apps and chatbots, focus on clean code and delightful UX. I enjoy solving problems and shipping small, maintainable systems.</p>
        <div style="margin-top:12px;">
          <span class="badge react">React</span>
          <span class="badge node">Node.js</span>
          <span class="badge tailwind">Tailwind</span>
          <span class="badge python">Python</span>
        </div>
      </div>

      <div class="card">
        <h3 style="color:#ffdede">Contact</h3>
        <p>Email: <a class="inline-link" href="mailto:dev.lawk3y@example.com">dev.lawk3y@example.com</a></p>
        <p>GitHub: <a class="inline-link" href="https://github.com/Dev-Lawk3y" target="_blank" rel="noopener">github.com/Dev-Lawk3y</a></p>
        <div style="margin-top:8px;">
          <a class="btn" href="https://twitter.com/Dev_Lawk3y" target="_blank" rel="noopener">Twitter</a>
          <a class="btn" href="https://www.linkedin.com/" target="_blank" rel="noopener">LinkedIn</a>
        </div>
      </div>
    </div>

    <footer>
      Made with ❤️ by <strong>Lawkey Marvelous</strong> — <a class="inline-link" href="https://github.com/Dev-Lawk3y" target="_blank" rel="noopener">github.com/Dev-Lawk3y</a>
    </footer>
  </div>

  <script>
    // Typing effect
    document.addEventListener("DOMContentLoaded", () => {
      const phrases = [
        "I build web apps that actually work. 💻",
        "Obsessed with clean code & smooth UX. 🧹",
        "Turning caffeine into code since 2023. ☕",
        "Your next favorite dev? 👀"
      ];

      let phraseIndex = 0;
      let charIndex = 0;
      const typewriter = document.getElementById('typewriter');

      function type() {
        const current = phrases[phraseIndex];
        if (charIndex < current.length) {
          typewriter.textContent += current.charAt(charIndex);
          charIndex++;
          setTimeout(type, 45);
        } else {
          setTimeout(erase, 900);
        }
      }

      function erase() {
        if (charIndex > 0) {
          typewriter.textContent = phrases[phraseIndex].substring(0, charIndex - 1);
          charIndex--;
          setTimeout(erase, 30);
        } else {
          phraseIndex = (phraseIndex + 1) % phrases.length;
          setTimeout(type, 500);
        }
      }

      // Start the loop
      type();
    });
  </script>
</body>
</html>