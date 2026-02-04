<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <title>Mgr. Pavla Svozilová – Logopedie</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Soukromá logopedická praxe v Brně. Individuální logopedická péče pro děti i dospělé.">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6;
      color: #222;
      background: #f7f7f7;
    }

    header {
      background: #ffffff;
      border-bottom: 1px solid #e0e0e0;
    }

    .container {
      width: 100%;
      max-width: 960px;
      margin: 0 auto;
      padding: 0 16px;
    }

    .topbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 16px 0;
      gap: 16px;
    }

    .logo-wrap {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .logo {
      width: 64px;
      height: 64px;
      border-radius: 50%;
      background: #e3edf7;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      color: #2a4d7a;
      font-size: 24px;
    }

    .brand-text {
      display: flex;
      flex-direction: column;
    }

    .brand-text h1 {
      font-size: 20px;
      font-weight: 600;
      color: #2a4d7a;
    }

    .brand-text span {
      font-size: 14px;
      color: #555;
    }

    nav a {
      margin-left: 16px;
      text-decoration: none;
      font-size: 14px;
      color: #2a4d7a;
      font-weight: 500;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: linear-gradient(135deg, #f3f7fc, #ffffff);
      padding: 40px 0 32px;
      border-bottom: 1px solid #e0e0e0;
    }

    .hero-inner {
      display: grid;
      grid-template-columns: minmax(0, 2fr) minmax(0, 1.5fr);
      gap: 32px;
      align-items: center;
    }

    .hero h2 {
      font-size: 28px;
      color: #2a4d7a;
      margin-bottom: 12px;
    }

    .hero p {
      font-size: 16px;
      color: #444;
      margin-bottom: 16px;
    }

    .hero ul {
      margin-left: 18px;
      margin-bottom: 16px;
    }

    .hero li {
      margin-bottom: 4px;
    }

    .hero-cta {
      margin-top: 8px;
    }

    .btn {
      display: inline-block;
      padding: 10px 18px;
      border-radius: 4px;
      border: none;
      cursor: pointer;
      font-size: 14px;
      font-weight: 500;
      text-decoration: none;
    }

    .btn-primary {
      background: #2a4d7a;
      color: #fff;
    }

    .btn-primary:hover {
      background: #223c5c;
    }

    .hero-image {
      width: 100%;
      max-width: 360px;
      justify-self: center;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 8px 20px rgba(0,0,0,0.08);
      background: #dfe9f5;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #2a4d7a;
      font-size: 18px;
      text-align: center;
      padding: 24px;
    }

    main {
      padding: 32px 0 40px;
    }

    section {
      margin-bottom: 32px;
      background: #ffffff;
      border-radius: 8px;
      padding: 24px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.03);
    }

    section h3 {
      font-size: 20px;
      color: #2a4d7a;
      margin-bottom: 12px;
    }

    section p {
      margin-bottom: 10px;
      color: #444;
    }

    section ul {
      margin-left: 18px;
    }

    section li {
      margin-bottom: 4px;
    }

    .contact-block p {
      margin-bottom: 6px;
    }

    footer {
      border-top: 1px solid #e0e0e0;
      padding: 16px 0;
      font-size: 13px;
      color: #777;
      background: #fafafa;
    }

    footer .container {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }

    @media (max-width: 768px) {
      .hero-inner {
        grid-template-columns: 1fr;
      }

      .topbar {
        flex-direction: column;
        align-items: flex-start;
      }

      nav {
        width: 100%;
      }

      nav a {
        margin-left: 0;
        margin-right: 16px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="container">
    <div class="topbar">
      <div class="logo-wrap">
        <div class="logo">
          PS
        </div>
        <div class="brand-text">
          <h1>Mgr. Pavla Svozilová</h1>
          <span>klinická logopedka</span>
        </div>
      </div>
      <nav>
        <a href="#o-mne">O mně</a>
        <a href="#zamereni">Zaměření</a>
        <a href="#kontakt">Kontakt</a>
      </nav>
    </div>
  </div>
</header>

<section class="hero">
  <div class="container hero-inner">
    <div>
      <h2>Soukromá logopedická praxe v&nbsp;Brně</h2>
      <p>
        Poskytuji individuální logopedickou péči dětem i dospělým. 
        Zaměřuji se na diagnostiku a terapii narušené komunikační schopnosti 
        v bezpečném a respektujícím prostředí.
      </p>
      <ul>
        <li>individuální logopedická terapie</li>
        <li>spolupráce s rodiči a školami</li>
        <li>dlouholetá praxe v oboru</li>
      </ul>
      <div class="hero-cta">
        <a href="#kontakt" class="btn btn-primary">Domluvit konzultaci</a>
      </div>
    </div>
    <div class="hero-image">
      <!-- Sem můžeš dát <img src="..." alt="..."> -->
      Fotografie nebo ilustrační obrázek<br>logopedické praxe
    </div>
  </div>
</section>

<main>
  <div class="container">

    <section id="o-mne">
      <h3>O mně</h3>
      <p>
        Jsem klinická logopedka s dlouholetou praxí v práci s dětmi i dospělými. 
        Věnuji se diagnostice a terapii narušené komunikační schopnosti, 
        především v oblasti výslovnosti, plynulosti řeči a jazykového vývoje.
      </p>
      <p>
        V terapii kladu důraz na individuální přístup, spolupráci s rodiči 
        a vytvoření bezpečného prostředí, ve kterém se klient může rozvíjet 
        vlastním tempem.
      </p>
    </section>

    <section id="zamereni">
      <h3>Zaměření</h3>
      <ul>
        <li>diagnostika a terapie narušené komunikační schopnosti</li>
        <li>poruchy výslovnosti (dyslálie)</li>
        <li>opožděný vývoj řeči</li>
        <li>jazykové a komunikační obtíže u dětí předškolního a mladšího školního věku</li>
        <li>spolupráce s rodiči, školkami a školami</li>
      </ul>
    </section>

    <section id="kontakt" class="contact-block">
      <h3>Kontakt</h3>
      <p><strong>Mgr. Pavla Svozilová</strong></p>
      <p><strong>E‑mail:</strong> <a href="mailto:info@logopedie-svozilova.cz">info@logopedie-svozilova.cz</a></p>
      <p><strong>Telefon:</strong> +420&nbsp;XXX&nbsp;XXX&nbsp;XXX</p>
      <p><strong>Lokalita:</strong> Brno a okolí</p>
    </section>

  </div>
</main>

<footer>
  <div class="container">
    <span>© <span id="year"></span> Mgr. Pavla Svozilová</span>
    <span>Soukromá logopedická praxe</span>
  </div>
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</footer>

</body>
</html>
