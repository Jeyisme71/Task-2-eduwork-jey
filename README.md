<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profil Biodata</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
 
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }

    /* ===== Section 1: Menu Navigasi ===== */
    nav {
      background-color: #add8e6;
      color: white;
    }

    .nav-container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      text-align: center;
    }

    .nav-container a {
      padding: 15px;
      display: block;
      text-decoration: none;
      color: white;
      transition: background 0.3s ease;
    }

    .nav-container a:hover {
      background-color: #555;
    }

    /* ===== Section 2: Judul dan Gambar ===== */
    #home {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      padding: 40px;
      gap: 20px;
      background-color: #f2f2f2;
    }

    #home .judul h1 {
      font-size: 2em;
      margin-bottom: 10px;
    }

    #home img {
      width: 100%;
      max-width: 350px;
      height: auto;
      border-radius: 10px;
      justify-self: end;
    }

    /* ===== Section 3: Biodata ===== */
    #biodata {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px;
      background-color: #fff;
    }

    .box {
      background-color: #e0e0e0;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    /* ===== Section 4: Portofolio ===== */
    #portofolio {
      padding: 40px;
      background-color: #f9f9f9;
    }

    #portofolio h2 {
      margin-bottom: 20px;
      text-align: center;
    }

    .portofolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }

    .portofolio-item {
      padding: 20px;
      border: 1px solid #ccc;
      background-color: white;
      border-radius: 8px;
    }

    .portofolio-item h3 {
      margin-bottom: 10px;
    }

    /* ===== Responsive Media Queries ===== */
    @media (max-width: 768px) {
      #home {
        grid-template-columns: 1fr;
        text-align: center;
      }

      #home img {
        justify-self: center;
      }

      .nav-container {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 480px) {
      #home .judul h1 {
        font-size: 1.5em;
      }

      nav a {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>

  <!-- Section 1: Menu Navigasi -->
  <nav>
    <div class="nav-container">
      <a href="#home">Header</a>
      <a href="#biodata">Biodata</a>
      <a href="#portofolio">Portofolio</a>
    </div>
  </nav>

  <!-- Section 2: Judul dan Gambar -->
  <section id="home">
    <div class="judul">
      <h2>Selamat Datang di Website Saya</h2>
      <p>Ini adalah contoh header dengan 2 dua kolom. kolom kiri berisi teks seperti ini</p>
      <button>Pelajari lebih lanjut</button>
      <br>
      
    </div>
    <img src="https://via.placeholder.com/350" alt="Foto Profil">
  </section>

  <!-- Section 3: Biodata -->
  <center>
      <h2>About Me</h2>
      <P>A brief Introduction about me</p>
      </center>
  <section id="biodata">
    <center>
    <div class="box"><strong>Full Name</strong> </div>
    </center>
    <center>
    <div class="box"><strong>Education</strong> </div>
     </center>
     <center>
    <div class="box"><strong>Pekerjaan</strong></div>
     </center>
     <center>
    <div class="box"><strong>Contact</strong> </div>
     </center>
     <center>
    <div class="box"><strong>Hobi</strong></div>
     </center>
     <center>
    <div class="box"><strong>Alamat</strong></div>
     </center>
  </section>

  <!-- Section 4: Portofolio -->
  <section id="portofolio">
    <h2>Portofolio</h2>
    <div> 
    <div class="portofolio-grid">
      <div class="portofolio-item">	
        <h3>Proyek 1</h3>        
        <p>Deskripai Proyek 1</p>
        <img src="https://via.placeholder.com/300x200" alt="gambar placeholder">
      </div>
      <div class="portofolio-item">
        <h3>Proyek 2</h3>
        <p>Deskripsi Proyek 2</p>
        <img src="https://via.placeholder.com/300x200" alt="gambar placeholder">
      </div>
      <div class="portofolio-item">
        <h3>Proyek 3</h3>
        <p>Deskripsi Proyek 3</p>
        <img src="https://via.placeholder.com/300x200" alt="gambar placeholder">
      </div>
      <div class="portofolio-item">
        <h3>Proyek 4</h3>
        <p>Deskripsi Proyek 4</p>
        <img src="https://via.placeholder.com/300x200" alt="gambar placeholder">
      </div>
      <div>
      <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <form>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
	
  </div>
</div>
    </div>
  </section>
  

</body>
</html>
