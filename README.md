<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Saya</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background-color: #f8f8f8; /* warna latar belakang soft */
    }

    header {
      background-color: #f08080; /* coklat susu gelap */
      color: white;
      padding: 30px 0;
      text-align: center;
    }

    nav {
      background-color: #cccccc; /* coklat susu medium */
      display: flex;
      justify-content: center;
    }

    nav a, .dropbtn {
      color: white;
      text-decoration: none;
      padding: 14px 20px;
      font-weight: bold;
      display: inline-block;
    }

    nav a:hover, .dropdown:hover .dropbtn {
      background-color: #f08080;
      border-radius: 5px;
    }

    /* Dropdown */
    .dropdown {
      position: relative;
      display: inline-block;
    }
    .dropdown-content {
      display: none;
      position: absolute;
      background: #ffc0cb;
      min-width: 160px;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
      border-radius: 5px;
    }
    .dropdown-content a {
      color: #333;
      padding: 10px 14px;
      display: block;
      text-decoration: none;
    }
    .dropdown-content a:hover {
      background: #f2e6da;
    }
    .dropdown:hover .dropdown-content {
      display: block;
    }

    section {
      display: none;
      padding: 40px;
      text-align: center;
    }
    section.active {
      display: block;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      display: inline-block;
    }

    button {
      background: #a9745b;
      color: white;
      padding: 8px 14px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }
    button:hover {
      background: #8c5e47;
    }

    input {
      padding: 5px;
      margin: 5px;
      border-radius: 4px;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>

  <header>
    <h1>⋆౨ৎ˚⟡ Syalwa Sasmita 𝜗𝜚˚⋆</h1>
    <p>Blog Website Saya</p>
  </header>

  <nav>
    <a href="web syalwa.html" onclick="showPage('beranda')">Beranda</a>
    <a href="tentang saya wawa.html" onclick="showPage('tentang')">Tentang Saya</a>
    <a href="jadwal wawa final.html" onclick="showPage('jadwal')">Jadwal Pelajaran</a>
    <a href="chord.html" onclick="showPage('syair')">Syair Lagu</a>
    <div class="dropdown">
      <a href="#" class="dropbtn">Menghitung ▼</a>
      <div class="dropdown-content">
        <a href="luas.html" onclick="showPage('luas')">Luas Persegi</a>
        <a href="volume.html" onclick="showPage('volume')">Volume Kotak</a>
      </div>
    </div>
  </nav>

  <!-- Halaman -->
  <section id="beranda" class="active">
    <div class="card">
      <h2>Hi! Selamat Datang~</h2>
      <p>Blog ini merupakan beranda Syalwa Sasmita siswi dari SMKN 1 Kota Tangerang.</p>
    </div>
  </section>

  <section id="tentang">
    <div class="card">
      <h2>Tentang Saya</h2>
      <p>Halo!, kenalin nama aku Syalwa dan ini adalah web pribadi tentang diri aku 𐙚⋆</p>
    </div>
  </section>

  <section id="jadwal">
    <div class="card">
      <h2>Jadwal Pelajaran</h2>
          <p>Berikut jadwal mingguan aku di kelas XII DKV 2 ˙𐃷˙</p>
 </div>
  </section>

  <section id="syair">
    <div class="card">
      <h2>Syair Lagu</h2>
      <p>Berisikan syair lagu favoriteku ✩♬ ₊˚.🎧⋆☾⋆⁺₊✧!</p>
    </div>
  </section>

  <section id="luas">
    <div class="card">
      <h2>Menghitung Luas Persegi</h2>
      <p>Masukkan panjang sisi:</p>
          </div>
  </section>

  <section id="volume">
    <div class="card">
      <h2>Menghitung Volume Kotak</h2>
      <p>Masukkan panjang, lebar, tinggi:</p>

    </div>
  </section>

  <script>
    function showPage(pageId) {
      let pages = document.querySelectorAll("section");
      pages.forEach(p => p.classList.remove("active"));
      document.getElementById(pageId).classList.add("active");
    }

   
      </script>

</body>
</html>
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <title>About Me - Syalwa Sasmita˚.🎀༘⋆</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #e3f2fd, #bbdefb);
      margin: 0;
      padding: 0;
    }
    header {
      text-align: center;
      background-color: #ffc0cb;
      color: white;
      padding: 20px 0;
    }
    header img {
      width: 150px;
      border-radius: 50%;
      margin-top: 15px;
    }
    section {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    h2 {
      color: #0d47a1;
      border-bottom: 2px solid #fe6074;
      padding-bottom: 5px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    table, th, td {
      border: 1px solid #fe6074;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    th {
      background-color: #ffc0cb;
      color: #0d47a1;
    }
    footer {
      text-align: center;
      background-color: #ffc0cb;
      color: white;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>⋆౨ৎ˚⟡ Syalwa Sasmita 𝜗𝜚˚⋆</h1>
    <p>Welcome to My Personal Page</p>
    <img src="C:\Users\MM-02\Pictures\Saved Pictures\wawa.jpeg">
  </header>

  <section>
    <h2>About Me!</h2>
    <p>Ola! Perkenalkan nama saya <strong>Syalwa Sasmita</strong>. Saya adalah seorang pelajar asal sekolah SMKN 1 Tangerang⋆. 𐙚 ˚ .

    Selain itu saya suka mempelajari hal-hal baru. 
    Dengan kepribadian saya yang suka mempelajari hal baru saya harap saya bisa mengembangkan ide yang saya miliki.</p>
  </section>

  <section>
    <h2>Hobi</h2>
    <table>
      <tr>
        <th>No</th>
        <th>Hobi</th>
      </tr>
      <tr>
        <td>1</td>
        <td>Menonton film 🎞️</td>
      </tr>
      <tr>
        <td>2</td>
        <td>Tidur 😴</td>
      </tr>
      <tr>
        <td>3</td>
        <td>Memasak 🍲</td>
      </tr>
    </table>
  </section>

  <section>
    <h2>Cita-Cita</h2>
    <p>Saya memiliki cita-cita untuk masuk perguruan tinggi ISI Jogja, dan juga saya meiliki cita-cita mempunyai kos-kosan.</p>
  </section>

  <footer>
    <p>&copy; 2025 Syalwa Sasmita𓇼 ⋆.˚ 𓆉 𓆝 𓆡⋆.˚ 𓇼🎀</p>
  </footer>

</body>
</html>
