<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PYK CYBER | LEADERS</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background: #000;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      overflow: hidden;
    }
    #particles-js {
      position: absolute;
      width: 100%;
      height: 100%;
      background: #000;
      z-index: -1;
    }
    .container {
      text-align: center;
      position: relative;
      top: 30%;
      transform: translateY(-30%);
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0.3em;
    }
    h2 {
      font-size: 1.5em;
      color: #0ff;
      margin-bottom: 1em;
    }
    p {
      color: #ccc;
    }
    .contact {
      margin-top: 2em;
      font-size: 1em;
    }
    .contact a {
      color: #0ff;
      text-decoration: none;
      margin: 0 10px;
    }
  </style>
</head>
<body>
  <div id="particles-js"></div>
  <div class="container">
    <h1>PYK CYBER</h1>
    <h2>LEADERS OF ETHICAL HACKING</h2>
    <p>Website resmi tim hacker Payakumbuh Cyber</p>
    <div class="contact">
      <a href="mailto:pykcyber@gmail.com">📧 pykcyber@gmail.com</a>
      <a href="https://wa.me/6283143490913">📱 WhatsApp</a>
    </div>
  </div>

  <!-- particles.js CDN -->
  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      particles: {
        number: { value: 80, density: { enable: true, value_area: 800 } },
        color: { value: "#00ffff" },
        shape: { type: "circle" },
        opacity: { value: 0.5 },
        size: { value: 3 },
        line_linked: { enable: true, distance: 150, color: "#0ff", opacity: 0.4, width: 1 },
        move: { enable: true, speed: 2 }
      }
    });
  </script>
</body>
</html>
