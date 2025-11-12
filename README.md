<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>EssyCoff — ERD & UI Gallery</title>
  <style>
    :root{--bg:#0f1720;--card:#111827;--muted:#9ca3af;--accent:#8fb28f;--gap:18px;--maxw:1100px}
    html,body{height:100%;margin:0;font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;color:#e6eef3;background:linear-gradient(180deg,#07101a 0%, #0b1720 100%);}
    .wrap{max-width:var(--maxw);margin:28px auto;padding:24px}
    header h1{margin:0;font-size:20px}
    header p{color:var(--muted);margin:6px 0 18px}

    section.card{background:rgba(255,255,255,0.02);border-radius:12px;padding:18px;margin-bottom:18px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    h2{margin:0 0 10px;font-size:16px}
    .note{color:var(--muted);font-size:13px;margin-bottom:12px}

    .figure{display:flex;gap:16px;flex-wrap:wrap}
    .figure figure{background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));padding:8px;border-radius:8px;flex:1 1 220px;min-width:180px;display:flex;flex-direction:column;align-items:center}
    .figure img{max-width:100%;height:auto;border-radius:6px;display:block}
    figcaption{margin-top:8px;font-weight:600;color:#e6eef3}
    .caption-muted{color:var(--muted);font-weight:400;font-size:13px}

    /* full-width image container */
    .fullimg{display:block;width:100%;overflow:hidden;border-radius:8px}
    .fullimg img{width:100%;height:auto;display:block}

    /* responsive grid for UI gallery */
    .ui-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:var(--gap);align-items:start}

    footer{color:var(--muted);font-size:13px;margin-top:8px}

    @media (max-width:640px){.wrap{padding:12px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <h1>EssyCoff Android — Dokumentasi Visual</h1>
      <p class="note">ERD, flowchart, dan screenshot UI. File HTML ini dibuat untuk ditampilkan sebagai halaman dokumentasi lokal/preview.</p>
    </header>

    <section class="card">
      <h2>ERD (Entity Relationship Diagram)</h2>
      <p class="note">Diagram hubungan tabel yang merepresentasikan struktur database aplikasi.</p>
      <div class="fullimg">
        <img alt="ERD EssyCoff" src="https://github.com/user-attachments/assets/746ce056-885e-4f7b-b269-04fe42a0c6e9" />
      </div>
    </section>

    <section class="card">
      <h2>Flowchart</h2>
      <p class="note">Alur proses utama aplikasi (Flowchart Essycoff - fasa version).</p>
      <div class="fullimg" style="margin-top:8px">
        <img alt="Flowchart EssyCoff" src="https://github.com/user-attachments/assets/c607e167-a225-4f91-a215-485c10f57c4c" />
      </div>
    </section>

    <section class="card">
      <h2>UI Screenshots</h2>
      <p class="note">Contoh tampilan layar aplikasi. Gunakan gambar berukuran serupa agar tata letak rapi di GitHub/HTML.</p>

      <div class="ui-grid" style="margin-top:12px">
        <figure>
          <img alt="Screenshot Dashboard" src="https://github.com/user-attachments/assets/89ce33ea-837b-4588-9f08-64a6f65c4140" />
          <figcaption>Dashboard<br><span class="caption-muted">Ringkasan & statistik</span></figcaption>
        </figure>

        <figure>
          <img alt="Screenshot Daftar Produk" src="https://github.com/user-attachments/assets/2513be54-b6fd-42a4-a7f1-41a051da8724" />
          <figcaption>Daftar Produk<br><span class="caption-muted">List & tindakan produk</span></figcaption>
        </figure>

        <figure>
          <img alt="Screenshot Transaksi" src="https://github.com/user-attachments/assets/40b69ecd-9784-4727-a908-e62ebf1832be" />
          <figcaption>Transaksi<br><span class="caption-muted">Form transaksi & keranjang</span></figcaption>
        </figure>

        <figure>
          <img alt="Screenshot Riwayat" src="https://github.com/user-attachments/assets/5d6529b5-1d1b-47d8-b255-91678ac9f95b" />
          <figcaption>Riwayat<br><span class="caption-muted">Daftar transaksi sebelumnya</span></figcaption>
        </figure>
      </div>

    </section>

    <footer>
      <p>Generated: HTML preview untuk README-style documentation — ganti src gambar sesuai lokasi repo kamu jika diperlukan.</p>
    </footer>
  </div>
</body>
</html>
