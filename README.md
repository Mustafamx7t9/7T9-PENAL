<!DOCTYPE html><html lang="en"><head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>𝟕𝑻𝟗 𝑷𝑬𝑵𝑨𝑳</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }body {
  background-color: #0e0e0e;
  color: #fff;
  overflow-x: hidden;
}

header {
  padding: 1rem 2rem;
  background-color: #000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #333;
}

.logo {
  font-size: 1.8rem;
  font-weight: bold;
  color: white;
  letter-spacing: 1px;
}

nav {
  background-color: #111;
  display: flex;
  justify-content: center;
  padding: 0.5rem;
  gap: 2rem;
}

nav a {
  color: #ccc;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

nav a:hover {
  color: #ff3333;
}

.carousel {
  width: 100%;
  max-width: 1280px;
  aspect-ratio: 16 / 9;
  margin: 2rem auto;
  position: relative;
  overflow: hidden;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
  background-color: #000;
}

.carousel img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  top: 0;
  left: 0;
  opacity: 0;
  transition: opacity 1s ease-in-out;
}

.carousel img.active {
  opacity: 1;
  z-index: 1;
}

.start-button,
.extra-buttons {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 1rem;
  margin: 1.5rem;
}

.start-button a,
.extra-buttons a {
  background-color: #ff3333;
  color: #fff;
  padding: 1rem 2.5rem;
  text-decoration: none;
  font-size: 1.1rem;
  font-weight: 600;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(255, 51, 51, 0.4);
  transition: background-color 0.3s, transform 0.2s;
  min-width: 260px;
  text-align: center;
}

.start-button a:hover,
.extra-buttons a:hover {
  background-color: #cc0000;
  transform: scale(1.05);
}

.middle-image {
  width: 100%;
  max-width: 1000px;
  margin: 2rem auto;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
}

.middle-image img {
  width: 100%;
  display: block;
}

.hidden-contact {
  display: none;
  text-align: center;
  margin-top: 1rem;
  background: #1a1a1a;
  padding: 1rem;
  border-radius: 10px;
}

.contact-show {
  display: block;
}

.hidden-contact a {
  display: block;
  margin: 0.5rem 0;
  color: #ff3333;
  text-decoration: none;
}

section {
  max-width: 1200px;
  margin: 2rem auto;
  padding: 1rem;
}

.section-title {
  font-size: 1.5rem;
  border-left: 4px solid #ff3333;
  padding-left: 1rem;
  margin-bottom: 1rem;
}

.dashboard-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
}

.card {
  background-color: #1a1a1a;
  padding: 1.2rem;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(255, 255, 255, 0.05);
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.card h3 {
  margin-bottom: 0.5rem;
  color: #ff3333;
}

.features {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  margin-top: 1rem;
}

.features div {
  flex: 1 1 300px;
  background: #1b1b1b;
  padding: 1rem;
  border-radius: 10px;
  border-left: 4px solid #ff3333;
}

footer {
  text-align: center;
  padding: 1rem;
  font-size: 0.9rem;
  background: #111;
  color: #aaa;
}

  </style>
</head><body>
  <header>
    <div class="logo">𝟕𝑻𝟗 𝑷𝑬𝑵𝑨𝑳 🚀</div>
  </header>  <nav>
    <a href="#home">Home</a>
    <a href="#dashboard">Dashboard</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>  <div id="home">
    <div class="carousel">
      <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1753223267/fwyiadqb7mphosqernsp.jpg" class="active" />
      <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1753223653/giaaxmiwbqpfzoaqdrv6.jpg" />
      <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1753223688/mqtkukvjmxctcogfzlzy.jpg" />
      <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1753277261/hji3edkp35gtftofs3gd.jpg" />
      <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1753277375/bbun6xwwykr0jqgwtxew.jpg" />
      <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1753277447/wels7or5cqcxdztxs1nt.jpg" />
    </div><div class="start-button">
  <a href="https://ad-freegames.github.io/" target="_blank">🎮 Start Game</a>
</div>
<span id="mini-clock" style="
  font-family: 'Orbitron', sans-serif;
  font-size: 16px;
  color: white;
  background: #111;
  padding: 4px 10px;
  border: 1px solid #ff2a2a;
  border-radius: 6px;
  box-shadow: 0 0 5px #ff2a2a88;
">
  --
</span>

<script>
  setInterval(() => {
    const now = new Date();
    const h = String(now.getHours()).padStart(2, '0');
    const m = String(now.getMinutes()).padStart(2, '0');
    const s = String(now.getSeconds()).padStart(2, '0');
    document.getElementById("mini-clock").innerText = `${h}:${m}:${s}`;
  }, 1000);
</script>
<section>
  <h2 class="section-title">✨ Features</h2>
  <div class="features">
    <div>
      <h3>🎮 Easy Access</h3>
      <p>Jump right into the game without login/signup hassle.</p>
    </div>
    <div>
      <h3>⚡ Fast Load</h3>
      <p>Optimized for speed with CDN image delivery.</p>
    </div>
    <div>
      <h3>📱 Mobile Friendly</h3>
      <p>Fully responsive design across all devices.</p>
    </div>
    <div>
      <h3>🛡️ Secure</h3>
      <p>No personal data collected or tracked. 100% safe.</p>
    </div>
  </div>
</section>
<a href="https://7t9-jarvis.zapier.app/" target="_blank" style="
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #111;
  color: white;
  padding: 10px 14px;
  border-radius: 50px;
  font-size: 12px;
  font-weight: bold;
  text-decoration: none;
  border: 1px solid #ff2a2a;
  box-shadow: 0 0 10px #ff2a2a88;
  z-index: 9999;
  transition: all 0.3s ease;
">
  🤖 AI Chat
</a>
<div class="middle-image">
  <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1753224976/mv6rhddemhrswztznud6.jpg" alt="Mid Image">
</div>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>𝟕𝑻𝟗 𝑷𝑬𝑵𝑨𝑳</title>
  <style>
    @font-face {
      font-family: "7t9Font";
      src: local("𝑭𝑶𝑵𝑻");
    }

    body {
      background: #000;
      color: white;
      text-align: center;
      padding-top: 60px;
      font-family: "7t9Font", serif;
    }

    .btn-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      margin-bottom: 30px;
    }

    .btn {
      padding: 8px 16px;
      border-radius: 6px;
      background: #cc2b2b;
      color: white;
      text-decoration: none;
      font-size: 17px;
      font-style: italic;
      font-weight: normal;
      font-family: "7t9Font", serif;
      letter-spacing: 0.3px;
      transition: 0.3s ease-in-out;
      min-width: 180px;
      border: none;
    }

    .btn:hover {
      background: #b22424;
      transform: scale(1.03);
    }

    #passwordPopup {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100vw;
      height: 100vh;
      background: rgba(0, 0, 0, 0.9);
      z-index: 9999;
      justify-content: center;
      align-items: center;
    }

    .popup-content {
      background: #1a1a1a;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 0 15px #cc2b2b;
      width: 90%;
      max-width: 400px;
      text-align: center;
    }

    .popup-content input {
      width: 100%;
      padding: 10px;
      border-radius: 6px;
      border: 1px solid #cc2b2b;
      background: #111;
      color: white;
      margin-top: 15px;
      font-family: "7t9Font", serif;
    }

    .popup-content button {
      margin-top: 15px;
      padding: 7px 16px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-family: "7t9Font", serif;
    }

    .access-btn {
      background: #cc2b2b;
      color: white;
      margin-right: 10px;
    }

    .cancel-btn {
      background: #444;
      color: white;
    }

    .error {
      color: #ff8080;
      display: none;
      margin-top: 10px;
    }

    .forgot {
      margin-top: 12px;
      font-size: 13px;
    }

    .forgot a {
      color: #888;
      text-decoration: underline;
      cursor: pointer;
    }

    .contact {
      margin-top: 25px;
      font-size: 15px;
      color: #aaa;
      font-family: "7t9Font", serif;
    }

    .contact b {
      color: #cc2b2b;
    }

    @media (max-width: 500px) {
      .btn {
        min-width: 100%;
      }
    }
  </style>
</head>
<body>

  <!-- BUTTONS -->
  <div class="btn-container">
    <a href="#" class="btn" onclick="openPasswordPopup()">🔐 𝟕𝑻𝟗 𝑻𝑬𝑹𝑴𝑰𝑵𝑨𝑳</a>
    <a href="https://poki.com" class="btn" target="_blank">🎮 𝑷𝑶𝑲𝑰 𝟕𝑻𝟗</a>
    <a href="https://wa.me/ais/1439468170806662?s=5" class="btn" target="_blank">🏆 𝑳𝑬𝑨𝑫𝑬𝑹𝑩𝑶𝑨𝑹𝑫</a>
    <a href="https://www.instagram.com/owner_aladdin_7t9?igsh=dDM0NnIwYWZkZXQw" class="btn" target="_blank">📱 𝑰𝑵𝑺𝑻𝑨𝑮𝑹𝑨𝑴</a>
  </div>

  <!-- POPUP -->
  <div id="passwordPopup">
    <div class="popup-content">
      <h3>🔑 Enter Password</h3>
      <input type="password" id="terminalPassword" placeholder="Enter Password" />
      <br />
      <button class="access-btn" onclick="checkPassword()">Access</button>
      <button class="cancel-btn" onclick="closePasswordPopup()">Cancel</button>
      <p class="error" id="errorText">❌ Incorrect Password</p>
      <p class="forgot"><a onclick="alert('Try remembering the correct password!')">Forgot Password?</a></p>
    </div>
  </div>

  <!-- CONTACT -->
  <div class="contact">
    📞 Contact: <b>03113921794</b>
  </div>

  <script>
    function openPasswordPopup() {
      document.getElementById("passwordPopup").style.display = "flex";
      document.getElementById("errorText").style.display = "none";
      document.getElementById("terminalPassword").value = "";
    }

    function closePasswordPopup() {
      document.getElementById("passwordPopup").style.display = "none";
    }

    function checkPassword() {
      const password = document.getElementById("terminalPassword").value;
      if (password === "KING7T9") {
        window.open("https://7t9jarvis.netlify.app/", "_blank");
        closePasswordPopup();
      } else {
        document.getElementById("errorText").style.display = "block";
      }
    }
  </script>

</body>
</html>

<div class="hidden-contact" id="contactBox">
  <a href="https://www.tiktok.com/@mustafa_king_7t9?_t=ZN-8yFguKP6VNe&_r=1" target="_blank">TikTok: @mustafa_king_7t9</a>
  <a href="https://www.instagram.com/owner_aladdin_7t9?igsh=dDM0NnIwYWZkZXQw" target="_blank">Instagram: owner_aladdin_7t9</a>
  <p>📞 Contact: 03113921794</p>
</div>
<!-- Add inside <body> of dashboard.html -->
<div id="welcomeModal" style="
  position: fixed; top: 0; left: 0; width: 100%; height: 100%;
  background: rgba(0,0,0,0.7); display: flex; align-items: center; justify-content: center;
  z-index: 9999;
">
  <div style="
    background: #1a1a1a; color: white; padding: 30px; border-radius: 12px;
    box-shadow: 0 0 20px rgba(255, 0, 0, 0.2); text-align: center;
  ">
  
    <h2>🎮 Welcome to your Dashboard</h2>
    <p>Mustafa King👑 -- Let's start your mission!</p>
    <button onclick="document.getElementById('welcomeModal').style.display='none'"
      style="margin-top: 15px; padding: 10px 20px; background: #e60000; color: white; border: none; border-radius: 6px;">
      Close
    </button>
  </div>
<style>
  body {
    animation: fadeIn 1.2s ease-in;
  }
  @keyframes fadeIn {
    from { opacity: 0; }
    to   { opacity: 1; }
  }
</style>

</div>
  </div>  <section id="dashboard">
    <h2 class="section-title">📊 Dashboard</h2>
    <div class="dashboard-grid">
      <div class="card">
        <h3>Performance</h3>
        <p>Track your game stats and player ranking in real-time.</p>
      </div>
      <div class="card">
        <h3>Settings</h3>
        <p>Customize game difficulty, theme, and control preferences.</p>
      </div>
      <div class="card">
        <h3>Leaderboard</h3>
        <p>See top players and your position among global gamers.</p>
      </div>
    </div>

<script>
function show(id) {
  document.getElementById("tab1").style.display = "none";
  document.getElementById("tab2").style.display = "none";
  document.getElementById(id).style.display = "block";
}
</script>
  </section>  <section id="about">
    <h2 class="section-title">ℹ️ About 𝟕𝑻𝟗 𝑷𝑬𝑵𝑨𝑳</h2>
    <p>
      𝟕𝑻𝟗 𝑷𝑬𝑵𝑨𝑳 is a next-generation digital gaming experience where simplicity meets high-quality performance. Dive into powerful, ad-free gameplay and an engaging player dashboard -- designed for the modern gamer.
    </p>
  </section>  <section id="contact">
    <h2 class="section-title">📬 Help Center</h2>
    <p>
      For any help or assistance, contact us at:
      <strong style="color: #ff3333;">0311-3921794</strong>
    </p>
    <p>
      Or email: <a href="mailto:support@7t9penal.com" style="color: #ff3333">support@7t9penal.com</a>
    </p>
<div style="text-align: center; margin-top: 20px; font-size: 14px; color: white;">
  <p>Provided by <span style="font-family: 'serif';">𝑴𝑼𝑺𝑻𝑨𝑭𝑨 𝑲𝑰𝑵𝑮 👑💗</span></p>
  <p>Provided by <span style="font-family: 'serif';">𝑳𝑨𝑰𝑩𝑨 𝑸𝑼𝑬𝑬𝑵 👑💗</span></p>
</div>
  </section>  <footer>
    &copy; 2025 𝟕𝑻𝟗 𝑷𝑬𝑵𝑨𝑳. All Rights Reserved.
  </footer> 
  
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI Assistant Only</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #111;
      color: white;
      font-family: 'Segoe UI', sans-serif;
    }

    .ai-box {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: #222;
      color: white;
      padding: 20px;
      border-radius: 20px 20px 5px 20px;
      max-width: 300px;
      box-shadow: 0 0 15px rgba(255, 0, 0, 0.3);
      z-index: 9999;
      animation: fadeIn 0.6s ease;
    }

    .ai-box p {
      margin: 0;
      font-size: 14px;
    }

    .ai-box strong {
      color: #e60000;
    }

    .ai-close {
      background: none;
      border: none;
      color: #e60000;
      font-size: 18px;
      position: absolute;
      top: 5px;
      right: 10px;
      cursor: pointer;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<input type="color" onchange="changeColor(this.value)">
<script>
function changeColor(color) {
  document.body.style.backgroundColor = color;
}

</script>
  <!-- AI Assistant Popup -->
  <div class="ai-box" id="aiBox">
    <button class="ai-close" onclick="document.getElementById('aiBox').style.display='none'">×</button>
    <p>🤖 <strong>AI Assistant:</strong> Welcome <strong>Mustafa King👑</strong>! Ready to dominate?</p>
  </div>
   <script>
    const images = document.querySelectorAll('.carousel img');
    let current = 0;

    function showNextImage() {
      images[current].classList.remove('active');
      current = (current + 1) % images.length;
      images[current].classList.add('active');
    }

    setInterval(showNextImage, 4000);

    function toggleContact() {
      const contactBox = document.getElementById('contactBox');
      contactBox.classList.toggle('contact-show');
    }
    
  </script></body></html>
  
