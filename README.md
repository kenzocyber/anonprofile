<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BLACK HAT</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0e0e0e;
      color: #e0e0e0;
      display: flex;
      justify-content: center;
      padding: 20px;
    }
    .container {
      max-width: 360px;
      width: 100%;
    }
    h1 {
      color: cyan;
      text-align: center;
    }
    .sub {
      text-align: center;
      color: #aaa;
      margin-bottom: 20px;
    }
    h2 {
      color: cyan;
      border-bottom: 1px solid #444;
      margin-top: 30px;
      margin-bottom: 10px;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .skill {
      flex: 1 1 45%;
      background: #1a1a1a;
      border-radius: 8px;
      padding: 10px;
      text-align: center;
      transition: 0.3s;
      cursor: pointer;
      font-size: 0.9rem;
      position: relative;
    }
    .skill:hover {
      background: #00d9ff33;
      transform: scale(1.05);
    }
    .skill i {
      color: cyan;
      font-size: 20px;
      margin-bottom: 5px;
      display: block;
    }
    .desc {
      display: none;
      font-size: 0.75rem;
      color: #ccc;
      margin-top: 5px;
      text-align: left;
    }
    .skill.active .desc {
      display: block;
    }
    ul {
      padding-left: 18px;
    }
    a {
      display: block;
      background: #1a1a1a;
      padding: 10px;
      margin-bottom: 8px;
      color: cyan;
      text-decoration: none;
      border-radius: 6px;
      transition: 0.2s;
    }
    a:hover {
      background: cyan;
      color: #000;
    }
    footer {
      text-align: center;
      font-size: 0.75rem;
      color: #777;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>BLACK HAT</h1>
    <p class="sub">Cyber Security Enthusiast</p>

    <h2>Skills</h2>
    <div class="skills">
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-bug"></i>Exploitation
        <div class="desc">Mengeksploitasi celah keamanan di sistem dan aplikasi.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fab fa-python"></i>Python
        <div class="desc">Membuat tools otomatisasi dan exploitasi.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-search"></i>OSINT
        <div class="desc">Mengumpulkan data publik dari internet.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-terminal"></i>Linux
        <div class="desc">Mengoperasikan sistem berbasis terminal.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-user-secret"></i>Engineering
        <div class="desc">Teknik manipulasi psikologis untuk akses sistem.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-toolbox"></i>Burp Suite
        <div class="desc">Analisa dan manipulasi trafik web.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-network-wired"></i>Nmap
        <div class="desc">Scanning dan pemetaan jaringan target.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-skull-crossbones"></i>Metasploit
        <div class="desc">Framework untuk membuat dan menjalankan exploit.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-wifi"></i>Wireshark
        <div class="desc">Menganalisa paket lalu lintas jaringan.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-screwdriver-wrench"></i>Reverse Eng.
        <div class="desc">Membongkar dan memahami program/software.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-lock"></i>Cryptography
        <div class="desc">Mengamankan data melalui teknik enkripsi.</div>
      </div>
      <div class="skill" onclick="toggleDesc(this)">
        <i class="fas fa-code"></i>Bash Scripting
        <div class="desc">Membuat script otomatisasi di Linux.</div>
      </div>
    </div>

    <h2>Projects</h2>
    <ul>
      <li>KenzoScan</li>
      <li>AnonTool</li>
      <li>OSINTer</li>
    </ul>

    <h2>Contact</h2>
    <a href="https://github.com/kenzocyber" target="_blank">GitHub</a>
    <a href="https://www.instagram.com/__21chochocaramel" target="_blank">Instagram</a>
    <a href="https://wa.me/6283143490913" target="_blank">WhatsApp</a>

    <footer>&copy; 2025 BLACK HAT</footer>
  </div>

  <script>
    function toggleDesc(el) {
      el.classList.toggle("active");
    }
  </script>
</body>
</html>
