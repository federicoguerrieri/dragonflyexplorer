<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>Dragonfly Explorer | Video Matrimonio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    :root {
      --primary: #5b7c99;      /* blu polvere wedding */
      --light-bg: #f7f8fa;
      --border: #e6e6e6;
      --text: #1f2937;
      --text-light: #4b5563;
      --accent: #d6bfa5;       /* beige wedding */
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #ffffff;
      color: var(--text);
      line-height: 1.6;
    }

    section {
      padding: 80px 12%;
    }

    h1, h2, h3 {
      font-weight: 600;
      margin-bottom: 16px;
    }

    p {
      max-width: 900px;
      margin-bottom: 12px;
      color: var(--text-light);
    }

    /* HERO */
    .hero {
      background: linear-gradient(135deg, #f7f8fa, #eef1f5);
      text-align: center;
      padding: 130px 20px;
    }

    .hero h1 {
      font-size: 2.6rem;
    }

    .hero p {
      font-size: 1.1rem;
      margin: 20px auto;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 14px 36px;
      background: var(--primary);
      color: white;
      border-radius: 6px;
      font-weight: 500;
      text-decoration: none;
    }

    /* GRID */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 32px;
      margin-top: 40px;
    }

    .box {
      border: 1px solid var(--border);
      padding: 32px;
      border-radius: 10px;
      background: white;
    }

    .box h3 {
      font-size: 1.1rem;
      color: var(--text);
    }

    /* SEZIONI ALTERNATE */
    .grey {
      background: var(--light-bg);
    }

    /* FAQ */
    .faq-item {
      border-bottom: 1px solid var(--border);
      padding: 20px 0;
    }

    /* CTA */
    .cta {
      background: var(--primary);
      color: white;
      text-align: center;
      padding: 110px 20px;
    }

    .cta p {
      color: #f1f5f9;
    }

    .cta .btn {
      background: white;
      color: var(--primary);
    }

    /* WHATSAPP */
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      padding: 14px 22px;
      border-radius: 50px;
      font-weight: 600;
      text-decoration: none;
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      z-index: 999;
    }

    footer {
      text-align: center;
      padding: 30px;
      font-size: 0.9rem;
      color: #6b7280;
    }

    footer a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 500;
    }

    @media (max-width: 768px) {
      section { padding: 60px 8%; }
      .hero h1 { font-size: 2.1rem; }
    }
  </style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <h1>Il video del vostro matrimonio</h1>
  <p>
    Siamo un team che realizza video di matrimonio semplici, eleganti
    e fedeli a ciò che vivrete nel vostro giorno più importante.
  </p>
  <a class="btn" href="mailto:info@dragonflyexplorer.it">Richiedi informazioni</a>
</section>

<!-- COSA FACCIAMO -->
<section>
  <h2>Cosa facciamo</h2>
  <p>
    Dragonfly Explorer realizza video di matrimonio seguendo l’intera giornata:
    dai preparativi alla festa.
    Lavoriamo in modo discreto per raccontare le emozioni reali,
    senza pose forzate.
  </p>
</section>

<!-- COME FUNZIONA -->
<section class="grey">
  <h2>Come funziona</h2>
  <div class="grid">
    <div class="box">
      <h3>1. Ci conosciamo</h3>
      <p>Ci raccontate il vostro matrimonio e verifichiamo la disponibilità.</p>
    </div>
    <div class="box">
      <h3>2. Il giorno delle nozze</h3>
      <p>Il nostro team vi segue con discrezione per tutta la giornata.</p>
    </div>
    <div class="box">
      <h3>3. Il vostro video</h3>
      <p>Ricevete il video montato, pronto da rivedere nel tempo.</p>
    </div>
  </div>
</section>

<!-- FAQ -->
<section>
  <h2>Domande frequenti</h2>

  <div class="faq-item">
    <h3>Quanto dura il video del matrimonio?</h3>
    <p>La durata varia in base alla giornata. Consegniamo sempre un video completo e uno più breve.</p>
  </div>

  <div class="faq-item">
    <h3>Quando riceveremo il video?</h3>
    <p>I tempi di consegna vengono concordati insieme prima del matrimonio.</p>
  </div>

  <div class="faq-item">
    <h3>Vi spostate anche fuori regione?</h3>
    <p>Sì, seguiamo matrimoni in tutta Italia e anche all’estero.</p>
  </div>
</section>

<!-- PRIVACY -->
<section class="grey">
  <h2>Privacy</h2>
  <p>
    I dati forniti tramite telefono o email vengono utilizzati solo
    per rispondere alle richieste degli sposi.
    Non vengono ceduti a terzi.
  </p>
</section>

<!-- CTA -->
<section class="cta">
  <h2>Volete sapere se siamo disponibili?</h2>
  <p>Scriveteci indicando la data e il luogo del vostro matrimonio.</p>
  <a class="btn" href="tel:+393490966957">Chiama ora</a>
</section>

<footer>
  © 2026 Dragonfly Explorer – Video Matrimonio<br>
  Tel: <a href="tel:+393490966957">349 096 6957</a> ·
  Email: <a href="mailto:info@dragonflyexplorer.it">info@dragonflyexplorer.it</a>
</footer>

<a class="whatsapp" href="https://wa.me/393490966957" target="_blank">
  WhatsApp
</a>

</body>
</html>
