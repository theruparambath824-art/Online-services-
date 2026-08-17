<!DOCTYPE html>
<html lang="ml">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Services | WhatsApp</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, "Noto Sans Malayalam", sans-serif;
      background: #f4f8ff;
      color: #10203a;
      line-height: 1.6;
    }

    header {
      background: white;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 12px rgba(0,0,0,0.08);
    }

    .logo {
      font-size: 22px;
      font-weight: bold;
      color: #0756b8;
    }

    .logo span {
      color: #16a34a;
    }

    .whatsapp-btn {
      background: #16a34a;
      color: white;
      padding: 10px 18px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      padding: 70px 6%;
      text-align: center;
      background: linear-gradient(135deg, #eaf4ff, #ffffff);
    }

    .badge {
      display: inline-block;
      background: #dcfce7;
      color: #087b35;
      padding: 7px 15px;
      border-radius: 20px;
      font-weight: bold;
      margin-bottom: 18px;
    }

    .hero h1 {
      font-size: clamp(35px, 7vw, 65px);
      line-height: 1.15;
      color: #073b8f;
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: #0b63ce;
    }

    .hero p {
      font-size: 19px;
      color: #64748b;
      max-width: 700px;
      margin: auto;
    }

    .hero-buttons {
      margin-top: 28px;
    }

    .main-btn {
      display: inline-block;
      background: #16a34a;
      color: white;
      padding: 15px 28px;
      border-radius: 12px;
      text-decoration: none;
      font-size: 17px;
      font-weight: bold;
      box-shadow: 0 10px 25px rgba(22,163,74,.25);
    }

    section {
      padding: 70px 6%;
    }

    .title {
      text-align: center;
      margin-bottom: 40px;
    }

    .title h2 {
      font-size: 34px;
      color: #073b8f;
      margin-bottom: 8px;
    }

    .title p {
      color: #64748b;
    }

    .services {
      max-width: 1100px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .service {
      background: white;
      padding: 25px;
      border-radius: 18px;
      border: 1px solid #e1e9f4;
      box-shadow: 0 8px 25px rgba(0,0,0,.05);
      transition: .2s;
    }

    .service:hover {
      transform: translateY(-5px);
    }

    .icon {
      font-size: 35px;
      margin-bottom: 12px;
    }

    .service h3 {
      color: #10203a;
      margin-bottom: 6px;
      font-size: 19px;
    }

    .service p {
      color: #64748b;
      font-size: 14px;
    }

    .steps-section {
      background: #eef6ff;
    }

    .steps {
      max-width: 1000px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 18px;
    }

    .step {
      background: white;
      padding: 25px;
      text-align: center;
      border-radius: 18px;
    }

    .number {
      width: 45px;
      height: 45px;
      background: #0756b8;
      color: white;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: auto auto 12px;
      font-weight: bold;
      font-size: 18px;
    }

    .contact {
      background: linear-gradient(135deg, #063987, #0b63ce);
      color: white;
      text-align: center;
    }

    .contact h2 {
      font-size: 35px;
    }

    .number-big {
      font-size: clamp(35px, 7vw, 60px);
      font-weight: bold;
      margin: 15px 0 25px;
    }

    .contact .main-btn {
      background: white;
      color: #087b35;
    }

    footer {
      background: #07162f;
      color: #b9c6d9;
      text-align: center;
      padding: 25px;
      font-size: 14px;
    }

    .floating-whatsapp {
      position: fixed;
      right: 18px;
      bottom: 18px;
      width: 60px;
      height: 60px;
      background: #16a34a;
      color: white;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 28px;
      text-decoration: none;
      box-shadow: 0 10px 25px rgba(0,0,0,.25);
      z-index: 200;
    }

    @media(max-width: 800px) {
      .services {
        grid-template-columns: repeat(2, 1fr);
      }

      .steps {
        grid-template-columns: repeat(2, 1fr);
      }
    }

    @media(max-width: 550px) {
      header {
        padding: 15px 4%;
      }

      .services,
      .steps {
        grid-template-columns: 1fr;
      }

      .hero {
        padding: 55px 5%;
      }

      section {
        padding: 55px 5%;
      }

      .hero h1 {
        font-size: 38px;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="logo">
    Online<span>Services</span>
  </div>

  <a class="whatsapp-btn"
     href="https://wa.me/918606093154?text=Hello%2C%20I%20need%20an%20online%20service."
     target="_blank">
    WhatsApp
  </a>
</header>


<!-- HERO -->

<section class="hero">

  <div class="badge">
    📲 WhatsApp Online Services
  </div>

  <h1>
    ഓൺലൈൻ കാര്യങ്ങൾ ഇനി<br>
    <span>തലവേദനയല്ല!</span>
  </h1>

  <p>
    ഇനി വീട്ടിൽ നിന്ന് തന്നെ WhatsApp വഴി
    ആവശ്യമായ Online Services എളുപ്പത്തിൽ ചെയ്യാം.
  </p>

  <div class="hero-buttons">

    <a class="main-btn"
       href="https://wa.me/918606093154?text=Hello%2C%20I%20need%20an%20online%20service."
       target="_blank">
      💬 WhatsApp ചെയ്യൂ
    </a>

  </div>

</section>


<!-- SERVICES -->

<section id="services">

  <div class="title">
    <h2>ഞങ്ങളുടെ സേവനങ്ങൾ</h2>

    <p>
      വിവിധ Online Services ഇനി WhatsApp വഴി എളുപ്പത്തിൽ.
    </p>
  </div>


  <div class="services">

    <div class="service">
      <div class="icon">🎓</div>
      <h3>College / Course Applications</h3>
      <p>College, course തുടങ്ങിയ അപേക്ഷകൾക്കുള്ള assistance.</p>
    </div>


    <div class="service">
      <div class="icon">📑</div>
      <h3>Certificate Services</h3>
      <p>വിവിധ certificate അപേക്ഷകൾക്കുള്ള സഹായം.</p>
    </div>


    <div class="service">
      <div class="icon">🪪</div>
      <h3>PAN / Aadhaar Services</h3>
      <p>PAN, Aadhaar സംബന്ധമായ Online Services.</p>
    </div>


    <div class="service">
      <div class="icon">🍚</div>
      <h3>Ration Card Services</h3>
      <p>Ration Card അപേക്ഷ, പുതുക്കൽ, മറ്റ് സേവനങ്ങൾ.</p>
    </div>


    <div class="service">
      <div class="icon">👶</div>
      <h3>Birth Certificate</h3>
      <p>Birth Certificate സംബന്ധമായ അപേക്ഷകളും assistance-ഉം.</p>
    </div>


    <div class="service">
      <div class="icon">✏️</div>
      <h3>Name Correction / Inclusion</h3>
      <p>പേര് തിരുത്തൽ, പേര് ഉൾപ്പെടുത്തൽ തുടങ്ങിയ services.</p>
    </div>


    <div class="service">
      <div class="icon">🛂</div>
      <h3>Passport Assistance</h3>
      <p>Passport application process-ൽ ആവശ്യമായ assistance.</p>
    </div>


    <div class="service">
      <div class="icon">🖨️</div>
      <h3>PDF & Document Services</h3>
      <p>PDF merge, split, convert, edit തുടങ്ങിയ services.</p>
    </div>


    <div class="service">
      <div class="icon">📸</div>
      <h3>Photo Resize & Editing</h3>
      <p>Photo resize, format മാറ്റൽ, basic editing services.</p>
    </div>


    <div class="service">
      <div class="icon">📄</div>
      <h3>Resume / CV Making</h3>
      <p>Professional Resume / CV തയ്യാറാക്കുന്നതിനുള്ള സഹായം.</p>
    </div>

  </div>

</section>


<!-- HOW IT WORKS -->

<section class="steps-section" id="how">

  <div class="title">
    <h2>എങ്ങനെ ഉപയോഗിക്കാം?</h2>

    <p>
      വളരെ എളുപ്പം — നാല് ഘട്ടങ്ങൾ മാത്രം.
    </p>
  </div>


  <div class="steps">

    <div class="step">
      <div class="number">1</div>
      <h3>WhatsApp ചെയ്യൂ</h3>
      <p>ഞങ്ങളുടെ നമ്പറിലേക്ക് message അയയ്ക്കുക.</p>
    </div>


    <div class="step">
      <div class="number">2</div>
      <h3>സേവനം പറയൂ</h3>
      <p>നിങ്ങൾക്ക് വേണ്ട service വ്യക്തമാക്കുക.</p>
    </div>


    <div class="step">
      <div class="number">3</div>
      <h3>Details നൽകൂ</h3>
      <p>ആവശ്യമായ വിവരങ്ങൾ നൽകുക.</p>
    </div>


    <div class="step">
      <div class="number">4</div>
      <h3>Service പൂർത്തിയാക്കാം</h3>
      <p>അടുത്ത നടപടികൾ അറിയിക്കും.</p>
    </div>

  </div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

  <h2>സേവനം ആവശ്യമുണ്ടോ?</h2>

  <p>
    വെറും ഒരു WhatsApp message മതി 👇
  </p>

  <div class="number-big">
    8606093154
  </div>

  <a class="main-btn"
     href="https://wa.me/918606093154?text=Hello%2C%20I%20need%20an%20online%20service."
     target="_blank">

    💬 WhatsApp ചെയ്യൂ

  </a>

</section>


<footer>
  © 2026 Online Services • WhatsApp Assistance
</footer>


<!-- FLOATING WHATSAPP BUTTON -->

<a class="floating-whatsapp"
   href="https://wa.me/918606093154?text=Hello%2C%20I%20need%20an%20online%20service."
   target="_blank">

  💬

</a>

</body>
</html>
