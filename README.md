<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BLACK HAT</title>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet" />
  <style>
    body {
      background-color: #111;
      color: #fff;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0 10px;
    }

    .container {
      max-width: 480px;
      margin: auto;
      padding: 20px 0;
    }

    h1, h2 {
      color: cyan;
      text-align: center;
    }

    p {
      text-align: center;
      color: #aaa;
    }

    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .card {
      background-color: #222;
      padding: 15px;
      border-radius: 12px;
      text-align: center;
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      background-color: #0a0a0a;
    }

    .card i {
      font-size: 28px;
      color: cyan;
      margin-bottom: 8px;
    }

    .card h3 {
      margin: 0;
      font-size: 18px;
    }

    .card p {
      font-size: 13px;
      color: #bbb;
    }

    .section-title {
      margin-top: 30px;
      margin-bottom: 10px;
      font-size: 22px;
      color: cyan;
      border-bottom: 1px solid #444;
      padding-bottom: 5px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>BLACK HAT</h1>
    <p>Cyber Security Enthusiast</p>

    <h2 class="section-title">Skills</h2>
    <div class="skills">
      <div class="card">
        <i class="fas fa-bug"></i>
        <h3>Exploitation</h3>
        <p>Mengeksploitasi celah keamanan di sistem dan aplikasi.</p>
      </div>
      <div class="card">
        <i class="fab fa-python"></i>
        <h3>Python</h3>
        <p>Membuat tools otomatisasi dan exploitasi.</p>
      </div>
      <div class="card">
        <i class="fas fa-search"></i>
        <h3>OSINT</h3>
        <p>Mengumpulkan data dari sumber terbuka.</p>
      </div>
      <div class="card">
        <i class="fas fa-terminal"></i>
        <h3>Linux</h3>
        <p>Menguasai command line dan sistem Linux.</p>
      </div>
      <div class="card">
        <i class="fas fa-user-secret"></i>
        <h3>Social Engineering</h3>
        <p>Manipulasi psikologis untuk akses informasi.</p>
      </div>
    </div>
  </div>
</body>
</html>
