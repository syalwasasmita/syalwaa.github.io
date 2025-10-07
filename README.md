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
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hitung Luas Persegi Panjang</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light d-flex align-items-center justify-content-center vh-100">

  <div class="container">
    <div class="row justify-content-center">
      <div class="col-md-5">
        <div class="card shadow-lg rounded-4">
          <div class="card-body p-4">
            <h3 class="card-title text-center mb-4">Hitung Luas Persegi Panjang</h3>
            <form id="luasForm">
              <div class="mb-3">
                <label for="panjang" class="form-label">Panjang</label>
                <input type="number" class="form-control" id="panjang" placeholder="Masukkan panjang" required>
              </div>
              <div class="mb-3">
                <label for="lebar" class="form-label">Lebar</label>
                <input type="number" class="form-control" id="lebar" placeholder="Masukkan lebar" required>
              </div>
              <button type="submit" class="btn btn-primary w-100">Hitung</button>
            </form>

            <div class="mt-4 text-center">
              <h5>Hasil:</h5>
              <p id="hasil" class="fw-bold fs-4 text-success">-</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

  <!-- JavaScript -->
  <script>
    document.getElementById("luasForm").addEventListener("submit", function(e) {
      e.preventDefault();
      const panjang = parseFloat(document.getElementById("panjang").value);
      const lebar = parseFloat(document.getElementById("lebar").value);

      if (panjang > 0 && lebar > 0) {
        const luas = panjang * lebar;
        document.getElementById("hasil").textContent = luas;
      } else {
        document.getElementById("hasil").textContent = "Masukkan angka yang valid!";
      }
    });
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Rahasia Cintaku – Kahitna | Chord & Lirik</title>
  <style>
    body {
      background: #ee687f;
      color: #f5f5f5;
      font-family: monospace;
      white-space: pre;
      padding: 20px;
      line-height: 1.6;
    }
    h1 {
      color: #b81466;
      margin-bottom: 20px;
    }
    .chord {
      color: #2c2cf6;
      font-weight: bold;
    }
  </style>
</head>
<body>

<h1>Rahasia Cintaku – Kahitna</h1>

<span class="chord">A                D        E</span>
Setiap di dekatmu hatiku meresah  
<span class="chord">A                   D            E</span>
Sesaat di sampingmu seakan kau milikku  
<span class="chord">D            C#m</span>
Kusadari aku tak seharusnya  
<span class="chord">Bm               E</span>
Terbawa perasaan  

<span class="chord">A              D</span>
Dan aku mencintaimu  
<span class="chord">Bm                         E</span>
Sungguh sungguh tanpa kau tahu  
<span class="chord">C#m            F#</span>
Tersimpan dalam hatiku  
<span class="chord">Bm        E              A</span>
Selamanya ini jadi rahasia cintaku  

<span class="chord">A                     D         E</span>
Sering aku meragu harus ku melangkah  
<span class="chord">A                    D        E</span>
Terkadang kau beri harapan, kadang terasa jauh  
<span class="chord">D              C#m</span>
Pedihnya hati bila ini  
<span class="chord">Bm               E</span>
Hanya terbawa perasaan  

<span class="chord">A              D</span>
Dan aku mencintaimu  
<span class="chord">Bm                         E</span>
Sungguh sungguh tanpa kau tahu  
<span class="chord">C#m            F#</span>
Tersimpan dalam hatiku  
<span class="chord">Bm        E              A</span>
Selamanya ini jadi rahasia cintaku  

</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menghitung Volume Kotak</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f9fa;
      text-align: center;
      padding: 50px;
    }
    .container {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      display: inline-block;
    }
    input {
      padding: 10px;
      margin: 10px;
      width: 200px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      padding: 10px 20px;
      background: #3498db;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #1e69de;
    }
    #hasil {
      margin-top: 20px;
      font-weight: bold;
    }
    a {
      display: inline-block;
      margin-top: 15px;
      text-decoration: none;
      color: #3498db;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>Menghitung Volume Kotak</h2>

    <input type="number" id="panjang" placeholder="Masukkan panjang">
    <br>
    <input type="number" id="lebar" placeholder="Masukkan lebar">
    <br>
    <input type="number" id="tinggi" placeholder="Masukkan tinggi">
    <br>
    <button onclick="hitungVolume()">Hitung</button>

    <p id="hasil"></p>

    <!-- Tombol kembali ke beranda -->
    <a href="index.html">← Kembali ke Beranda</a>
  </div>

  <script>
    function hitungVolume() {
      let p = document.getElementById("panjang").value;
      let l = document.getElementById("lebar").value;
      let t = document.getElementById("tinggi").value;

      if (p && l && t) {
        let volume = p * l * t;
        document.getElementById("hasil").innerText = 
          "Volume kotak adalah: " + volume;
      } else {
        document.getElementById("hasil").innerText = 
          "Mohon isi semua nilai!";
      }
    }
  </script>

</body>
</html>
