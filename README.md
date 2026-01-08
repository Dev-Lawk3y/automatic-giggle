<!-- 🎨 Colorful, Typing Effect README.md – Copy & Paste Me! -->

<div align="center">
  <h1 style="color:                                                                       
  <p style="font-size:1.2em; color:#4facfe;">Web Developer | Problem Solver | Coffee Lover ☕</p>
</div>

---

### 🖋️ Typing Effect (Auto-animated!)
<div id="typewriter" style="font-family:monospace; font-size:1.5em; white-space:pre; border-right: 2px solid                                                                                                                  
</div>

<script>
  const phrases = [
    "I build web apps that actually work. 💻",
    "Obsessed with clean code & smooth UX. 🧹",
    "Turning caffeine into code since 2023. ☕",
    "Your next favorite dev? 👀",
  ];

  let phraseIndex = 0;
  let charIndex = 0;
  const typewriter = document.getElementById('typewriter');

  function type() {
    if (charIndex < phrases[phraseIndex].length) {
      typewriter.textContent += phrases[phraseIndex][charIndex];
      charIndex++;
      setTimeout(type, 50);
    } else {
      setTimeout(erase, 1000);
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

  type();
</script>

---

                                                 
<style>
  @keyframes color-change {
    0% { color:           
    25% { color:           
    50% { color:           
    75% { color:           
    100% { color:           
  }
</style>

---

                          
<div style="display:flex; gap:10px; flex-wrap:wrap; margin:20px 0;">
  <div style="flex:1; min-width:200px; background:#2c3e50; padding:15px; border-radius:8px; color:#ecf0f1;">
    <h3 style="color:                        
    <p>Built with React + Tailwind</p>
    <a href="#" style="color:#3498db;">View Live</a>
  </div>
  <div style="flex:1; min-width:200px; background:                                                          
    <h3 style="color:#e74c3c;">Project 2</h3>
    <p>Node.js + MongoDB</p>
    <a href="                                       
  </div>
</div>

---

                      
<div style="display:flex; gap:10px; flex-wrap:wrap; margin:20px 0;">
  <span style="background:#3498db; color:#fff; padding:5px 10px; border-radius:5px;">React</span>
  <span style="background:                                                                         
  <span style="background:#f1c40f; color:#000; padding:5px 10px; border-radius:5px;">Python</span>
  <span style="background:                                                                          
</div>

---

                         
<div style="margin-top:20px;">
  <a href="newlawkey@gmail.com" style="color:#3498db; margin-right:10px;">📧 Email</a>
  <a href="https:                                                                             
  <a href="https://twitter.com/you" style="color:#3498db;">Twitter</a>
</div>

---

<div align="center" style="margin-top:30px; font-size:0.8em; color:          
  Made with ❤️ by [Lawkey Marvelous] — <a href="https://github.com/Dev-Lawk3y" style="color:#3498db;">github.com/Dev-Lawk3y</a>
</div>
