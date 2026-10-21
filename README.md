
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portofolio seni digital Rizky Angila Pradani, Juara 3 Komik Digital FLS3N 2025 Kabupaten Batang.">
  <title>Rizky Angila Pradani | Portofolio</title>
  <style>
    :root {
      --bg: #100b0e;
      --panel: #1a1116;
      --wine: #8f2446;
      --rose: #e5a2b7;
      --white: #f8f0f2;
      --muted: #c6b5bd;
    }

    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      background:
        radial-gradient(ellipse at top right,
        #431725 0%, transparent 40%),
        var(--bg);
      color: var(--white);
      font-family: Arial, sans-serif;
      line-height: 1.7;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .wrap {
      width: min(1050px, 90%);
      margin: auto;
    }

    header {
      padding: 22px 0;
      border-bottom: 1px solid #ffffff20;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 15px;
    }

    .brand {
      font-weight: bold;
      letter-spacing: 2px;
    }

    .brand span { color: var(--rose); }

    .navlinks {
      display: flex;
      gap: 20px;
      color: var(--muted);
      font-size: 14px;
    }

    .hero {
      padding: 75px 0;
      display: grid;
      grid-template-columns: 1.3fr 0.8fr;
      gap: 35px;
      align-items: center;
    }

    .eyebrow {
      color: var(--rose);
      font-size: 12px;
      letter-spacing: 3px;
      text-transform: uppercase;
      font-weight: bold;
    }

    h1 {
      font-size: clamp(42px, 7vw, 78px);
      line-height: 1.05;
      margin: 18px 0;
      letter-spacing: -2px;
    }

    h1 em {
      color: var(--rose);
      font-style: normal;
    }

    .lead {
      color: var(--muted);
      max-width: 580px;
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 25px;
    }

    .btn {
      padding: 11px 18px;
      border: 1px solid #ffffff30;
      border-radius: 30px;
      display: inline-block;
      font-weight: bold;
      font-size: 14px;
    }

    .btn.primary {
      background: var(--wine);
      border-color: var(--wine);
    }

    .award {
      padding: 28px;
      border: 1px solid #e5a2b750;
      border-radius: 24px;
      background: linear-gradient(145deg, #431725, var(--panel));
      box-shadow: 0 20px 60px #0005;
    }

    .medal {
      font-size: 38px;
      margin-bottom: 15px;
    }

    .award h2 {
      font-size: 30px;
      line-height: 1.2;
      margin: 10px 0;
    }

    .award p { color: var(--muted); }

    section { padding: 45px 0; }

    .section-title {
      font-size: clamp(28px, 4vw, 42px);
      line-height: 1.2;
      margin: 8px 0;
    }

    .sub {
      color: var(--muted);
      max-width: 650px;
    }

    .about-grid,
    .achievement-grid {
      display: grid;
      grid-template-columns: 0.8fr 1.2fr;
      gap: 18px;
      margin-top: 25px;
    }

    .panel {
      background: #1a1116cc;
      border: 1px solid #ffffff20;
      border-radius: 22px;
      padding: 25px;
    }

    .monogram {
      min-height: 190px;
      display: grid;
      place-items: center;
      border-radius: 18px;
      background: linear-gradient(135deg, #431725, #171015);
      color: var(--rose);
      font-size: 65px;
      font-weight: bold;
      letter-spacing: -5px;
    }

    .panel h3 { margin-top: 0; }

    .panel p { color: var(--muted); }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 18px;
    }

    .tag {
      border: 1px solid #ffffff25;
      border-radius: 20px;
      padding: 5px 11px;
      font-size: 12px;
    }

    .achievement-grid { grid-template-columns: 1fr 1fr; }

    .number {
      font-size: 55px;
      font-weight: bold;
      color: var(--rose);
      line-height: 1.2;
    }

    .details {
      list-style: none;
      padding: 0;
    }

    .details li {
      border-top: 1px solid #ffffff20;
      padding: 10px 0;
      display: flex;
      justify-content: space-between;
      gap: 12px;
      font-size: 13px;
    }

    .details span { color: var(--muted); }

    .certificate {
      min-height: 220px;
      padding: 20px;
      border: 1px dashed #e5a2b780;
      border-radius: 18px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: var(--muted);
    }

    .certificate .icon { font-size: 40px; }

    .note {
      margin-top: 18px;
      padding: 18px;
      border-left: 3px solid var(--rose);
      background: #8f244620;
      color: var(--muted);
      border-radius: 0 12px 12px 0;
    }

    footer {
      margin-top: 45px;
      padding: 25px 0;
      border-top: 1px solid #ffffff20;
      color: var(--muted);
      font-size: 12px;
    }

    @media (max-width: 700px) {
      .hero,
      .about-grid,
      .achievement-grid {
        grid-template-columns: 1fr;
      }

      .hero { padding: 50px 0; }
      section { padding: 35px 0; }
      .monogram { min-height: 140px; }
      .navlinks { gap: 12px; font-size: 12px; }
      .brand { font-size: 12px; }
    }
  </style>
</head>

<body>
<header>
  <div class="wrap">
    <nav>
      <a class="brand" href="#home">RAP<span>.</span> PORTOFOLIO</a>
      <div class="navlinks">
        <a href="#tentang">Tentang</a>
        <a href="#prestasi">Prestasi</a>
        <a href="#karya">Dokumentasi</a>
      </div>
    </nav>
  </div>
</header>

<main>
  <div class="wrap hero" id="home">
    <div>
      <div class="eyebrow">Portofolio seni digital</div>
      <h1>Ide, cerita,<br><em>dan karya.</em></h1>
      <p class="lead">
        Halo, aku <strong>Rizky Angila Pradani</strong>, siswi
        SMA Negeri 1 Bawang yang tertarik pada dunia seni
        dan bercerita melalui visual. Halaman ini menjadi
        ruang untuk mendokumentasikan pencapaian dan
        perjalanan berkarya.
      </p>
      <div class="buttons">
        <a class="btn primary" href="#prestasi">Lihat prestasi ↘</a>
        <a class="btn" href="#tentang">Kenali aku</a>
      </div>
    </div>

    <div class="award">
      <div class="medal">🏆</div>
      <div class="eyebrow">Pencapaian unggulan · 2025</div>
      <h2>Juara 3<br>Komik Digital</h2>
      <p>FLS3N tingkat Kabupaten Batang</p>
    </div>
  </div>

  <section id="tentang">
    <div class="wrap">
      <div class="eyebrow">Sedikit tentangku</div>
      <h2 class="section-title">Berkarya dengan cerita.</h2>
      <p class="sub">
        Seni adalah cara untuk menuangkan ide, mengolah
        imajinasi, dan menyampaikan cerita melalui gambar.
      </p>

      <div class="about-grid">
        <div class="monogram">RAP</div>
        <div class="panel">
          <h3>Rizky Angila Pradani</h3>
          <p>
            Siswi SMA Negeri 1 Bawang dengan minat pada seni
            visual dan komik digital. Portofolio ini dibuat
            sebagai dokumentasi perjalanan kreatif dan
            pencapaian di bidang seni.
          </p>
          <div class="tags">
            <span class="tag">Seni digital</span>
            <span class="tag">Komik</span>
            <span class="tag">Ilustrasi</span>
            <span class="tag">Visual storytelling</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="prestasi">
    <div class="wrap">
      <div class="eyebrow">Pencapaian</div>
      <h2 class="section-title">Satu langkah yang berarti.</h2>
      <p class="sub">
        Sebuah pencapaian yang menjadi penyemangat untuk
        terus belajar dan mengembangkan karya.
      </p>

      <div class="achievement-grid">
        <div class="panel">
          <div class="number">03</div>
          <div class="eyebrow">Juara ketiga</div>
          <h3>Komik Digital — FLS3N 2025</h3>
          <p>Tingkat Kabupaten Batang</p>

          <ul class="details">
            <li><span>Nama</span><strong>Rizky Angila Pradani</strong></li>
            <li><span>Sekolah</span><strong>SMA Negeri 1 Bawang</strong></li>
            <li><span>Tanggal sertifikat</span><strong>28 Mei 2025</strong></li>
          </ul>
        </div>

        <div class="panel" id="karya">
          <div class="eyebrow">Dokumentasi</div>
          <h3>Sertifikat penghargaan</h3>
          <div class="certificate">
            <div class="icon">📜</div>
            <strong>Tempat dokumentasi sertifikat</strong>
            <p>Foto sertifikat asli bisa ditambahkan di bagian ini.</p>
          </div>
        </div>
      </div>

      <div class="note">
        Galeri karya dapat ditambahkan kapan saja.
        Untuk saat ini, halaman ini berfokus pada dokumentasi
        prestasi Komik Digital FLS3N 2025.
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    © 2025 Rizky Angila Pradani · Portofolio pribadi
  </div>
</footer>
</body>
</html>
