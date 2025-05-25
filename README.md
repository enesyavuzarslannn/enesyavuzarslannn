<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Enes Yavuzarslan – Siber Güvenlik</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0c0c0c;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    header {
      margin-top: 30px;
      font-family: 'Orbitron', sans-serif;
      font-size: 2.5rem;
      color: #00ffe5;
      animation: fadeIn 3s ease-in-out;
      text-align: center;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    section {
      margin: 30px auto;
      width: 90%;
      max-width: 1000px;
      text-align: center;
    }

    h2 {
      border-bottom: 2px solid #00ffe5;
      padding-bottom: 5px;
      margin-bottom: 20px;
      color: #00ffe5;
    }

    .icons, .tools, .certs, .projects {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    .icons a, .tools div {
      background: #1c1c1c;
      padding: 10px;
      border-radius: 10px;
      transition: 0.3s ease;
    }

    .icons a:hover, .tools div:hover {
      transform: scale(1.1);
      background-color: #222;
    }

    .icons img, .tools img {
      width: 40px;
      height: 40px;
    }

    .certs ul {
      list-style: none;
      padding: 0;
    }

    .certs li {
      margin: 8px 0;
    }

    .project-card {
      background-color: #1e1e1e;
      padding: 15px;
      border-radius: 12px;
      text-align: left;
      max-width: 450px;
    }

    .projects {
      gap: 20px;
    }

    .project-card h3 {
      margin-top: 0;
      color: #00ffe5;
    }

    .project-card a {
      text-decoration: none;
      color: white;
      background-color: #00ffe5;
      padding: 5px 10px;
      margin-right: 10px;
      border-radius: 6px;
      font-size: 0.9rem;
      transition: 0.3s ease;
    }

    .project-card a:hover {
      background-color: #00bba8;
    }

    footer {
      margin: 40px 0 20px;
      font-size: 0.9rem;
      color: gray;
    }
  </style>
</head>
<body>
  <header id="animated-header">Siber Güvenlik Portföyü – Enes Yavuzarslan</header>

  <section>
    <h2>Bildiğim ve Öğrendiğim Diller</h2>
    <div class="icons">
      <a href="https://html.spec.whatwg.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/></a>
      <a href="https://www.w3.org/Style/CSS/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/></a>
      <a href="https://www.php.net/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg"/></a>
      <a href="https://devdocs.io/c/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg"/></a>
      <a href="https://isocpp.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg"/></a>
      <a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg"/></a>
      <a href="https://www.javascript.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"/></a>
      <a href="https://www.python.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/></a>
    </div>
  </section>

  <section class="certs">
    <h2>Sertifikalar</h2>
    <ul>
      <li>Cybersecurity for Everyone – University of Maryland</li>
      <li>Introduction to Cybersecurity – IBM</li>
      <li>Kali Linux – Board Infinity</li>
      <li>NVIDIA – Introduction to Networking</li>
      <li>Google Cybersecurity Professional Certificate</li>
      <li>Introduction to Cybersecurity – Cisco Networking Academy</li>
      <li>Microsoft – Cybersecurity Tools & Technologies</li>
      <li>Turkcell Geleceği Yazanlar – Pentesting Eğitimi</li>
    </ul>
  </section>

  <section class="tools">
    <h2>Kullandığım Araçlar</h2>
    <div><img src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Kali-dragon-icon.svg" title="Kali Linux" /></div>
    <div><img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Burp_Suite_logo.png" title="Burp Suite" /></div>
    <div><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" title="VSCode"/></div>
    <div><img src="https://nmap.org/images/nmap-logo-64x64.png" title="Nmap" /></div>
    <div><img src="https://icons.iconarchive.com/icons/papirus-team/papirus-apps/512/bettercap-icon.png" title="Bettercap" /></div>
    <div><img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Network_Computer_icon.svg" title="Netdiscover" /></div>
  </section>

  <section class="projects">
    <h2>Projelerim</h2>
    <div class="project-card">
      <h3>Port Scan Simulator</h3>
      <p>Port tarama mantığını öğretmek için tasarlanmış simülasyon.</p>
      <a href="https://github.com/enesyavuzarslann/port-scan-simulator" target="_blank">Kod</a>
    </div>
    <div class="project-card">
      <h3>Phishing Login Simulation</h3>
      <p>Kimlik avı saldırısı örneği, eğitim amacıyla hazırlanmış.</p>
      <a href="https://github.com/enesyavuzarslann/phishing-login-simulation" target="_blank">Kod</a>
    </div>
    <div class="project-card">
      <h3>Password Strength Simulation</h3>
      <p>Şifre güvenliğini görsel olarak değerlendirme aracı.</p>
      <a href="https://github.com/enesyavuzarslann/password-strength-simulation" target="_blank">Kod</a>
    </div>
    <div class="project-card">
      <h3>Keylogger Educational Simulation</h3>
      <p>Klavye giriş takibi nedir, nasıl işler? Eğitim amaçlı demo.</p>
      <a href="https://github.com/enesyavuzarslann/keylogger-educational-simulation" target="_blank">Kod</a>
    </div>
    <!-- Diğer projeler de benzer şekilde eklenebilir -->
  </section>

  <footer>
    © 2025 Enes Yavuzarslan – Tüm hakları saklıdır.
  </footer>

  <script>
    const header = document.getElementById('animated-header');
    let titleText = header.innerText;
    let i = 0;

    function animateText() {
      if (i < titleText.length) {
        header.innerHTML = titleText.substring(0, i + 1);
        i++;
        setTimeout(animateText, 80);
      }
    }

    header.innerHTML = "";
    animateText();
  </script>
</body>
</html>
