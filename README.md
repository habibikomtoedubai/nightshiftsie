<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Night Shift</title>
  <style>
    :root {
      --bg: #0a0a12;
      --panel: #121826;
      --panel2: #1b2333;
      --text: #f3f4f6;
      --muted: #cbd5e1;
      --accent: #ffca5f;
      --accent2: #7dd3fc;
      --border: #2e3a4f;
      --green: #1fa76a;
    }

    * { box-sizing: border-box; }
    body {
      margin: 0;
      background:
        linear-gradient(rgba(10,10,18,0.7), rgba(10,10,18,0.9)),
        radial-gradient(circle at top, rgba(125,211,252,0.15), transparent 30%),
        var(--bg);
      color: var(--text);
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.7;
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 48px 20px 80px;
    }

    .hero {
      padding: 32px 0 18px;
      border-bottom: 1px solid rgba(255,255,255,0.08);
      margin-bottom: 30px;
    }

    h1 {
      margin: 0;
      font-size: clamp(2.4rem, 5vw, 4.2rem);
      letter-spacing: 1px;
      color: var(--accent);
    }

    .subtitle {
      margin-top: 12px;
      color: var(--muted);
      font-size: 1.1rem;
      max-width: 760px;
    }

    .buttons {
      margin-top: 24px;
      display: flex;
      flex-wrap: wrap;
      gap: 14px;
    }

    .btn {
      display: inline-block;
      padding: 14px 22px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: 700;
      transition: 0.2s ease;
      border: 1px solid transparent;
    }

    .btn.primary {
      background: var(--accent);
      color: #111827;
    }

    .btn.secondary {
      background: transparent;
      color: var(--text);
      border-color: var(--border);
    }

    .btn:hover {
      transform: translateY(-1px);
      opacity: 0.95;
    }

    .grid {
      display: grid;
      grid-template-columns: 1.6fr 0.8fr;
      gap: 26px;
    }

    .panel {
      background: rgba(18, 24, 38, 0.92);
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 26px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.18);
    }

    .panel h2 {
      margin-top: 0;
      font-size: 1.7rem;
      color: var(--accent2);
    }

    p {
      font-size: 1.04rem;
      color: var(--muted);
      margin: 0 0 18px;
    }

    .feature-list {
      list-style: none;
      padding: 0;
      margin: 0;
      display: grid;
      gap: 12px;
    }

    .feature-list li {
      padding: 12px 14px;
      border: 1px solid var(--border);
      border-radius: 10px;
      background: rgba(255,255,255,0.02);
      color: var(--text);
    }

    .side-box {
      display: grid;
      gap: 18px;
    }

    .meta-card {
      background: rgba(18, 24, 38, 0.92);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 20px;
    }

    .meta-card h3 {
      margin: 0 0 12px;
      font-size: 1.1rem;
      color: var(--accent);
    }

    .meta-card ul {
      list-style: none;
      margin: 0;
      padding: 0;
      color: var(--muted);
    }

    .meta-card li {
      margin: 8px 0;
    }

    @media (max-width: 760px) {
      .grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="hero">
      <h1>Night Shift</h1>
      <div class="subtitle">
        Gece vardiyası, karanlık koridorlar, kaybolan işaretler ve hayatta kalma mücadelesi...
      </div>
      <div class="buttons">
        <a class="btn primary" href="#">Demo Oyna</a>
        <a class="btn secondary" href="#">Tam Sürüm</a>
      </div>
    </header>

    <div class="grid">
      <section class="panel">
        <h2>Hikâye</h2>
        <p>
          Night Shift, terk edilmiş bir iş yerinde çalışan bir kişinin gece vardiyasında
          her şeyin kontrol dışına çıktığı bir korku deneyimidir. Karanlık koridorlar,
          kapalı odalar, sessizlik ve bilinmeyen sesler, oyuncunun kalbine korku salarken
          aynı zamanda gerilim ve keşif duygusunu da güçlendirir. Oyun, yalnızlığın ve
          umutsuzluğun pekiştiği bir atmosferde ilerler ve her kapı, her ışık, her ses
          yeni bir gizem doğurur. Karakter, sadece hayatta kalmak için değil, aynı zamanda
          geride bıraktığı gerçeği anlamak için de mücadele eder.
        </p>
        <p>
          Her bölümde yeni bir ipucu, her köşede bir tehdit ve her adımda derinleşen
          bir gerilim vardır. Oyuncu, sınırlı kaynaklarla ilerler, ortamı dikkatlice
          inceler ve hayatta kalmayı kabullendiği anda gerçek tehlike başlar. Night Shift,
          basit ama etkili mekaniklerle sürükleyici, atmosferik ve zihin yorucu bir
          deneyim sunar.
        </p>
        <ul class="feature-list">
          <li>✔ Gerilim dolu atmosfer ve sessiz, karanlık ortam tasarımı</li>
          <li>✔ Keşif, gizem ve hayatta kalma odaklı oynanış</li>
          <li>✔ Kısa ama etkili hikâye anlatımı ve sürükleyici sahneler</li>
          <li>✔ Düşünceli kaynak yönetimi ve korku dolu kararlar</li>
        </ul>
      </section>

      <aside class="side-box">
        <div class="meta-card">
          <h3>Detaylar</h3>
          <ul>
            <li>Tür: Korku / Gerilim</li>
            <li>Mod: Tek kişilik</li>
            <li>Platform: Web / PC</li>
            <li>Durum: Demo</li>
          </ul>
        </div>

        <div class="meta-card">
          <h3>Özellikler</h3>
          <ul>
            <li>Atmosferik ses tasarımı</li>
            <li>Gizemli arka plan</li>
            <li>Yavaş, gerilim dolu tempo</li>
            <li>Hayatta kalma odaklı ilerleyiş</li>
          </ul>
        </div>
      </aside>
    </div>
  </div>
</body>
</html>
