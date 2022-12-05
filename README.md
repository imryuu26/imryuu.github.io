<!doctype html>
<html lang="en" id="rumah" >
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Naufal Fadhilah</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/style.css">
    </head>
  <body>

 <!--navbar -->
<nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top ">
  <div class="container-fluid">
    <a class="navbar-brand halaman-tegar" href="#rumah">Naufal Fadhilah</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-sm-0">
        <li class="nav-item">
          <a class="nav-link halaman-tegar" aria-current="page" href="#tentang">Tentang</a>
        </li>
        <li class="nav-item">
          <a class="nav-link halaman-tegar" href="#portofolio">Portofolio</a>
        </li>
        
        <li class="nav-item">
          <a class="nav-link halaman-tegar" href="#kontak">Kontak</a>
        </li>

        <li class="nav-item">
          <a class="nav-link halaman-tegar" href="#alamat">Alamat</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success " type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
 <!--#endnavbar -->


 <!--jumbotron -->
<!--<div id="carouselExampleSlidesOnly" class="carousel slide jumbotron bg-light col-8-sm text-center py-2" data-bs-ride="carousel">-->
<!--  <div class="carousel-inner">-->
<!--    <div class="carousel-item active">-->
<!--      <img src="foto/desa.jpg" class="d-block w-100" alt="..." >-->
<!--    </div>-->
<!--    <div class="carousel-item">-->
<!--      <img src="foto/desa.jpg" class="d-block w-100" alt="..." >-->
<!--    </div>-->
<!--    <div class="carousel-item">-->
<!--      <img src="foto/desa.jpg" class="d-block w-100" alt="..." >-->
<!--    </div>-->
<!--  </div>-->
  
<!--  <h1 class="display-5 fw-bold"> Selamat Datang Diweb Gulak Galik</h1>-->
<!--  <p class="fs-4"> <a href="">Instagram</a> | <a  href="">whatsapp</a> | <a href="">telegram</a></p>-->
<!--</div>-->


       <div class="jumbotron text-center  bg-light col-12-sm fs-4 py-5 ">
        <br>
        <img  src="foto/naufal.jpg" class="rounded-circle" alt="" >
        <h1 class="display-5 fw-bold"> Naufal Fadhilah</h1>
        <p class="fs-4"> <a href="https://www.instagram.com/naufalfadhilah1/">Instagram</a> | <a  href="">whatsapp</a> | <a href="">telegram</a></p>   
      </div> 

<!-- jumbotron end-->

    
<!-- #tentang -->
  <section class="tentang" id="tentang">
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-sm-12 py-4">
          <h2 class="text-center">Tentang</h2>
          <hr>
        </div>
      </div>
    </div>
    
      <div class="row justify-content-center">
        <div class="col-sm-5 py-4">
            
            <p>Saya Lahir di Jakarta 26 Mei 2002 dan saya pindah ke Bandar Lampung Pada waktu smp karena orang tua saya 
                dan saya mlanjutkan SMK di SMK BKB (Bangun Nusa Bangsa) setelah lulus saya melanjutkan ke perguruan tinggi Universitas Teknokrat Indonesia
            </p>
        </div>
        <div class="col-sm-5 py-4">
           
            <p>Saya Suka bermain Game Dan Membaca Komik
            </p>
        </div>
      </div>
  </section>
<!-- #endtentang -->


<!-- #portofolio -->
<section class="portofolio" id="portofolio">
  <div class="container-fluid">
    <div class="row justify-content-center ">
      <div class="col-sm-12 text-center py-4">
        <h2>Portofolio</h2>
        <hr>
      </div>
    </div>

    <div class="row ">
      <div class="col-sm-4 py-4">
        <img src="foto/portofolio.jpg" class="img-thumbnail" alt="...">  
      </div>
    </div>
  </div>
</section>
<!-- #endportofolio -->

<!-- #kontak -->
<section class="kontak" id="kontak">
  <div class="container-fluid">
    <div class="row justify-content-center">
      <div class="col-sm-12 text-center py-4">
        <h2>Kontak</h2>
        <hr>
      </div>
    </div>

    <div class="row justify-content-center">
      <div class="col-sm-8 py-4">
        <form>
          <div class="form-grup">
            <label for="nama">Nama</label>
            <input type="text" id="nama" class="form-control" placeholder="Masukan Nama Anda">
          </div>
          
          <div class="py-4">
            <div class="form-grup">
              <label for="email">Email</label>
              <input type="email" id="email" class="form-control" placeholder="Masukan Email Anda">
            </div>
          </div>
          
           
            <div class="form-grup py-4">
              <label for="tel">No Telepon </label>
              <input type="tel" id="tel" class="form-control" placeholder="Masukan Nomor Telepon Anda">
            </div>
          

        <!--<div class="py-4">-->
        <!--  <select class="form-control" name="" id="" >-->
        <!--    <option value="">--Pilih Kategori--</option>-->
        <!--    <option>Ktp</option>-->
        <!--    <option>Kartu keluarga</option>-->
        <!--  </select>-->
        <!--</div>-->

          <div class="form-grup py-4">
            <label for="pesan">Pesan</label>
            <textarea name="" id="" class="form-control " rows="10" placeholder="Masukan Pesan"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Kirim Pesan</button>
        </form>
      </div>
    </div>
  </div>
</section>
<!-- #end kontak -->



<section class="alamat" id="alamat">
  <div class="container-fluid">
    <div class="row justify-content-center">
      <div class="col-sm-12 py-4">
        <h2 class="text-center">Alamat</h2>
        <hr>
      </div>
    </div>
  </div>

  <div class="row justify-content-center">
    <div class="col-sm-10">
      <div class="ratio ratio-16x9">
        <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3972.007656478219!2d105.24738931448613!3d-5.415802455593705!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e40da5b68bd8c8d%3A0x3f5e4a724f66a86b!2sPerumahan%20Kaliawi%20Permai%20Blok%20C%2012!5e0!3m2!1sid!2sid!4v1670258418331!5m2!1sid!2sid"
        title=""
        allowfullscreen>
        </iframe>
      </div>
      <div class="row justify-content-center">
        <div class="col-sm-10">
          <br>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- #footer -->
<footer>
<div class="container-fluid">
  <div class="row justify-content-center">
    <div class="col-sm-5">
      <p class="text-center">&copy; copyright2022 | Make it by <i class="glyphicon glyphicon-heart"></i><a href="">Naufal Fadhilah</a>.</p>

      <i class="glyphicon-heart"></i>
    </div>
  </div>
</div>
</footer>
<!-- #endfooter -->



<script src="js/jquery-3.6.1.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/scroll.js"></script>
<script src="js/jquery.easing.1.3.js"></script>
  </body>
</html>
