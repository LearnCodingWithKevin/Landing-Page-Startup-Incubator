<template>
  <section id="welcome-kevins">
    <div class="container-fluid px-0">
      <div class="row">
        <div class="col-lg-6">
          <div id="welcome-left-image">
            <div class="well-come-box-left">
              <h3>Ciptakan Inovasimu sekarang!</h3>
              <p>Bangun tim startup dengan ilmu dan jejaring strategis</p>
              <a href="#get-free">Mari Berkoneksi</a>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="row welcome-right-content">
            <div class="welcome-right-title">
              <h4>Welcome To Kevin Startup Digital</h4>
              <h2>Apa sih Kevin Startup Digital itu?</h2>
              <p>
                Kevin Startup Digital adalah upaya baru membantu penggerak ekosistem startup digital Indonesia untuk saling terkoneksi, saling berbagi pengetahuan dan pengalaman. <br />Diinisiasi Sejak 2022, gerakan ini diharapkan mendorong
                terciptanya mencetak startup yang menjadi solusi atas masalah dengan memanfaatkan teknologi digital .
              </p>
            </div>
            <div class="col-lg-6 High-Quality">
              <img src="../assets/images/Tujuan.png" alt="" />
              <h3>
                Kevin Startup Digital<br />
                Tujuan
              </h3>
              <p>Memberikan peluang kewirausahawan berbasis teknologi digital ke seluruh penjuru nusantara.</p>
            </div>
            <div class="col-lg-6 High-Quality">
              <img src="../assets/images/FokusProgram.svg" alt="" />
              <h3>Fokus Program</h3>
              <p>Mendorong terwujudnya ekosistem startup digital yang kolaboratif dan inklusif dengan visi menciptakan solusi bagi permasalahan bangsa memanfaatkan teknologi digital.</p>
            </div>
            <div class="get-free-btn">
              <a href="#get-free">Daftar Sekarang <b-icon-arrow-right></b-icon-arrow-right></a>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-lg-6">
          <div class="welcome-right-content why-choose-left">
            <div class="welcome-right-title why-choose-title">
              <h4>Why Choose Us</h4>
              <h2>Tempat yang tepat untuk belajar, berjejaring dan tumbuh sebagai Startup Founder</h2>
              <p>Tingkatkan kualitasmu sebagai founder pemula dan bangun startup yang lebih baik</p>
            </div>
            <div class="why-list">
              <ul>
                <li>
                  <span><i class="fa-solid fa-check"></i></span>Mentor Ahli
                </li>
                <li>
                  <span><i class="fa-solid fa-check"></i></span>Akses Seumur Hidup
                </li>
                <li>
                  <span><i class="fa-solid fa-check"></i></span>Pembelajaran Jarak Jauh
                </li>
                <li>
                  <span><i class="fa-solid fa-check"></i></span>Gratis
                </li>
              </ul>
            </div>
            <div class="get-free-btn">
              <a href="#service">Lihat Program <b-icon-arrow-down></b-icon-arrow-down></a>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div id="why-choose-right"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'WelcomeKevins',
};
</script>

<style scoped>
#welcome-left-image {
  background-image: linear-gradient(#0117326b, #0117326b), url('../assets/images/FemaleProgrammer.jpg');
}

#why-choose-right {
  background-image: linear-gradient(#0117326b, #0117326b), url('../assets/images/FemaleProgrammer2.jpg');
}
</style>
