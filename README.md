<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enes Yavuzarslan - Siber Güvenlik Portföyü</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2d9d6c6c1.js" crossorigin="anonymous"></script>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Orbitron', sans-serif;
      background-color: #0e0e0e;
      color: #f0f0f0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
    }
    h1 {
      font-size: 2.8rem;
      margin-bottom: 20px;
      animation: fadeInDown 2s ease-out forwards;
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-40px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .certificates, .languages, .tools, .projects {
      margin: 40px 0;
      text-align: center;
    }
    .section-title {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #00ffc8;
    }
    ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }
    ul li {
      background-color: #1e1e1e;
      padding: 10px 20px;
      border-radius: 12px;
      font-size: 1rem;
      transition: transform 0.3s;
    }
    ul li:hover {
      transform: scale(1.05);
      background-color: #272727;
    }
    .icons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
    }
    .icons a {
      color: #00ffc8;
      font-size: 2rem;
      transition: transform 0.3s, color 0.3s;
    }
    .icons a:hover {
      transform: scale(1.2);
      color: #00ff88;
    }
    .tools img {
      width: 50px;
      height: 50px;
      filter: brightness(1.3);
      transition: transform 0.3s;
    }
    .tools img:hover {
      transform: scale(1.2);
    }
    .project-card {
      background-color: #1e1e1e;
      padding: 20px;
      margin: 10px;
      border-radius: 12px;
      max-width: 300px;
      text-align: center;
    }
    .project-links a {
      color: #00ffc8;
      margin: 0 10px;
      text-decoration: none;
    }
    .project-links a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1>Enes Yavuzarslan</h1>

  <section class="certificates">
    <div class="section-title">Sertifikalar</div>
    <ul>
      <li>Cybersecurity for Everyone - University of Maryland</li>
      <li>Introduction to Cybersecurity - IBM</li>
      <li>Kali Linux Board Infinity</li>
      <li>NVIDIA Networking</li>
      <li>Google Cybersecurity Certificate</li>
      <li>Introduction to Cybersecurity - Cisco Networking Academy</li>
      <li>Microsoft Cybersecurity Tools</li>
      <li>Turkcell Pentesting Eğitimi</li>
    </ul>
  </section>

  <section class="languages">
    <div class="section-title">Bildiklerim</div>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>PHP</li>
      <li>C</li>
      <li>C++</li>
      <li>C#</li>
      <li>JavaScript</li>
      <li>Python</li>
    </ul>
  </section>

  <section class="tools">
    <div class="section-title">Kullandığım Araçlar</div>
    <div class="icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" title="Kali Linux"/>
      <img src="https://www.svgrepo.com/show/354202/vscode.svg" title="VSCode"/>
      <img src="https://nmap.org/images/nmap-logo-256x256.png" title="Nmap"/>
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Burp_Suite_logo.png" title="Burp Suite"/>
      <img src="https://www.wireshark.org/assets/images/logo.png" title="Wireshark"/>
      <img src="https://avatars.githubusercontent.com/u/2918581?s=280&v=4" title="Metasploit"/>
      <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" title="Git"/>
      <img src="https://www.vectorlogo.zone/logos/docker/docker-icon.svg" title="Docker"/>
      <img src="https://www.vectorlogo.zone/logos/virtualbox/virtualbox-icon.svg" title="VirtualBox"/>
      <img src="https://seeklogo.com/images/P/postman-logo-F43375A2EB-seeklogo.com.png" title="Postman"/>
    </div>
  </section>

  <section class="projects">
    <div class="section-title">Projeler</div>
    <div class="icons">
      <div class="project-card">
        <h3>Port Scan Simulator</h3>
        <p>Port taramanın nasıl çalıştığını gösteren simülasyon.</p>
        <div class="project-links">
          <a href="https://github.com/enesyavuzarslann/port-scan-simulator" target="_blank">Kod</a>
        </div>
      </div>
      <div class="project-card">
        <h3>Phishing Login Sim</h3>
        <p>Oltalama saldırısının temel yapısını simüle eder.</p>
        <div class="project-links">
          <a href="https://github.com/enesyavuzarslann/phishing-login-simulation" target="_blank">Kod</a>
        </div>
      </div>
      <!-- Diğer projeleri buraya benzer şekilde ekleyebilirim -->
    </div>
  </section>

  <section class="icons">
    <a href="https://github.com/enesyavuzarslann" target="_blank"><i class="fab fa-github"></i></a>
    <a href="https://linkedin.com/in/enesyavuzarslann" target="_blank"><i class="fab fa-linkedin"></i></a>
    <a href="https://medium.com/@enesyavuzarslann" target="_blank"><i class="fab fa-medium"></i></a>
  </section>
</body>
</html>
