<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>TRIVANA Café & Wellness</title>
  <style>
    :root{
      --bg:#f6f1ec;
      --brown:#2b241f;
      --gold:#d4af37;
      --card:#ffffff;
      --muted:#6b5b50;
      --radius:12px;
      --shadow:0 6px 18px rgba(43,36,32,0.1);
      --maxw:1100px;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:"Poppins",sans-serif;
      background:var(--bg);
      color:var(--brown);
      line-height:1.5;
    }
    header{
      background:linear-gradient(180deg,var(--brown),#1d1714);
      color:var(--gold);
      text-align:center;
      padding:40px 16px;
    }
    header h1{font-size:2.2rem;margin-bottom:6px;letter-spacing:1px}
    nav{
      background:#3b2f2a;
      display:flex;
      justify-content:center;
      flex-wrap:wrap;
      gap:16px;
      padding:10px 20px;
      position:sticky;
      top:0;
      z-index:50;
    }
    nav a{
      color:#fff;
      text-decoration:none;
      font-weight:600;
      transition:0.3s;
    }
    nav a:hover{color:var(--gold);}
    .container{
      max-width:var(--maxw);
      margin:30px auto;
      padding:0 20px;
    }
    .hero{
      background:url('https://images.unsplash.com/photo-1555396273-367ea4eb4db5?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1074') center/cover no-repeat;
      border-radius:16px;
      color:#fff;
      padding:90px 24px;
      text-align:center;
      position:relative;
      overflow:hidden;
      box-shadow:var(--shadow);
    }
    .hero::after{
      content:"";
      position:absolute;
      inset:0;
      background:rgba(0,0,0,0.45);
    }
    .hero .inner{
      position:relative;
      z-index:1;
      max-width:800px;
      margin:auto;
    }
    .hero h2{font-size:2.2rem;margin-bottom:12px}
    .hero p{opacity:.95}
    .btn{
      display:inline-block;
      background:var(--gold);
      color:var(--brown);
      font-weight:700;
      border-radius:8px;
      padding:12px 18px;
      text-decoration:none;
      margin-top:18px;
    }
    h2.section-title{
      border-left:6px solid var(--gold);
      padding-left:10px;
      margin:40px 0 18px;
    }
    .card{
      background:var(--card);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:14px;
      text-align:center;
    }
    .card img{
      width:100%;
      height:180px;
      object-fit:cover;
      border-radius:10px;
      background:#ddd;
    }
    .row{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
      gap:20px;
    }
    footer{
      background:var(--brown);
      color:#fff;
      text-align:center;
      padding:20px 10px;
      margin-top:40px;
    }
    .muted{color:var(--muted)}
  </style>
</head>
<body>

<header>
  <h1>TRIVANA</h1>
  <p>Café • Gym • Salon</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#facilities">Fasilitas</a>
  <a href="#menu">Menu</a>
  <a href="#salon">Salon</a>
  <a href="#gallery">Galeri</a>
  <a href="#booking">Booking</a>
</nav>

<main class="container">
  <!-- Hero -->
  <section id="home" class="hero" style="background-image:url('https://images.unsplash.com/photo-1498654896293-37aacf113fd9?auto=format&fit=crop&w=1500&q=80');">
    <div class="inner">
      <h2>Selamat Datang di TRIVANA</h2>
      <p>Nikmati suasana hangat dan elegan, tempat di mana kopi, kenyamanan, dan perawatan diri berpadu sempurna.</p>
      <a href="#booking" class="btn">Booking Sekarang</a>
    </div>
  </section>

  <!-- Fasilitas -->
  <h2 class="section-title" id="facilities">Fasilitas Kami</h2>
  <div class="row">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1542181961-9590d0c79dab?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170" alt="Foto Café (tambahkan sendiri)">
      <h3>Café Area</h3>
      <p class="muted">Suasana hangat dengan pilihan kopi dan pastry terbaik.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1758957646695-ec8bce3df462?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1332" alt="Foto Gym (tambahkan sendiri)">
      <h3>Gym Modern</h3>
      <p class="muted">Peralatan lengkap untuk mendukung gaya hidup sehat.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1706629504952-ab5e50f5c179?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170" alt="Foto Salon (tambahkan sendiri)">
      <h3>Salon Elegan</h3>
      <p class="muted">Rasakan perawatan premium dari tenaga profesional.</p>
    </div>
  </div>

  <!-- Menu -->
  <h2 class="section-title" id="menu">Menu Café</h2>
  <div class="row">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1534234757579-8ad69d218ad4?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170" alt="https://images.unsplash.com/photo-1534234757579-8ad69d218ad4?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170">
      <h3>Cappuccino</h3>
      <p class="muted">Espresso lembut dengan susu foam creamy.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1681218079567-35aef7c8e7e4?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1074" alt="Foto Menu 2">
      <h3>Butter Croissant</h3>
      <p class="muted">Pastry lembut dan renyah khas Prancis.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1604298458655-ae6e04213678?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=687" alt="Foto Menu 3">
      <h3>Caramel Late</h3>
      <p class="muted">Kopi susu dengan sentuhan karamel manis.</p>
    </div>
  </div>

  <!-- Salon -->
  <h2 class="section-title" id="salon">Salon TRIVANA</h2>
  <div class="row">
    <div class="card">
      <img src="https://plus.unsplash.com/premium_photo-1667516650977-b6fb6e3a5a5f?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1172" alt="Foto Hair Spa">
      <h3>Hair Spa</h3>
      <p class="muted">Perawatan rambut menenangkan dan menyegarkan.</p>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1570172619644-dfd03ed5d881?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1170" alt="Foto Facial">
      <h3>Facial Treatment</h3>
      <p class="muted">Membersihkan dan menutrisi kulit wajah.</p>
    </div>
  </div>

  <!-- Galeri -->
  <h2 class="section-title" id="gallery">Galeri Interior</h2>
  <div class="row">
    <div class="card"><img src="https://images.unsplash.com/photo-1676275322337-dee7519f648a?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=687" alt="https://images.unsplash.com/photo-1680528221511-e495d841c4e5?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=987"></div>
    <div class="card"><img src="https://images.unsplash.com/photo-1680528221511-e495d841c4e5?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=987" alt="Foto Interior 2"></div>
    <div class="card"><img src="https://images.unsplash.com/photo-1759376928130-415a2e369c3e?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&q=80&w=1074" alt="Foto Interior 3"></div>
  </div>

  <!-- Booking -->
  <h2 class="section-title" id="booking">Booking Online</h2>
  <p class="muted">Silakan lakukan pemesanan melalui form online berikut:</p>
  <p style="margin-top:10px;">
    <a href="https://docs.google.com/forms/d/e/1FAIpQLSeQ416_uyXWSHKgjYy5oA0alo8swsePUqQBGzxIf0SDONgQLQ/viewform?usp=header"
       class="btn" target="_blank" rel="noopener">Buka Form Booking</a>
  </p>
</main>

<footer>
  <small>© 2025 TRIVANA Café & Wellness — Semua Hak Dilindungi</small>
</footer>

</body>
</html>