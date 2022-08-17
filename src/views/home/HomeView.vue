<script setup>
import NavbarComponent from "@/components/medium/NavbarComponent.vue";
</script>
<template>
  <NavbarComponent></NavbarComponent>
  <section class="landing-hero text-center">
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-12 col-sm-8">
          <div class="title-landing">
            Pengembang Situs Web, Aplikasi Web, Aplikasi Seluler
          </div>
          <p class="desc-landing mt-4">
            Memberikan solusi digital untuk menyelesaikan masalah Anda.
          </p>
          <div class="mt-4">
            <a href="" class="btn btn-primary btn-blue">
              <img src="/images/whatsapp.png" alt="" style="width: 14px" />
              Konsultasi Gratis
            </a>
            <a href="" class="btn btn-outline-white ms-4" target="_blank">
              Lihat layanan
              <img
                src="/icons/arrow_right.svg"
                alt=""
                style="width: 14px"
                class="ms-2"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="our-feature mt-5">
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-12 col-sm-8">
          <div class="row">
            <div class="col-12 text-center">
              <h2 class="text-white">Our Feature</h2>
            </div>
          </div>
          <div class="row mt-5 justify-content-center">
            <div class="col-6 col-sm-6 col-md-4 box-feature">
              <center>
                <img src="/images/maven.png" alt="team" style="width: 100%" />
              </center>
              <br />
              <b> Digitization </b>
              <p class="mt-4">
                Mengedepankan solusi digital dalam setiap aspek permasalahan
                Anda. Bersama kami, efisiensi dengan sistem membantu Anda
                mencapai tujuan yang lebih efektif.
              </p>
            </div>
            <div class="col-6 col-sm-6 col-md-4 box-feature">
              <center>
                <img
                  src="/images/solutions.png"
                  alt="team"
                  style="width: 100%"
                />
              </center>
              <br />
              <b> User Friendly </b>
              <p class="mt-4">
                Sebuah website, sistem, atau aplikasi mobile jika tidak ramah
                dengan user tidak ada gunanya. Bersama kami, kami menyediakan
                solusi yang ramah dengan user.
              </p>
            </div>
            <div class="col-6 col-sm-6 col-md-4 box-feature">
              <center>
                <img src="/images/team.png" alt="team" style="width: 100%" />
              </center>
              <br />
              <b> Zero Down-Time </b>
              <p class="mt-4">
                Jika website, sistem, atau aplikasi mobile mengalami gangguan,
                maka Anda tidak bisa mengaksesnya. Bersama kami, kami
                memeliharanya dengan baik.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="clients mt-5">
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-12 col-sm-8">
          <div class="row">
            <div class="col-12">
              <h4 class="text-white">
                Kami dipercaya memberikan solusi kepada :
              </h4>
            </div>
          </div>
          <div class="row mt-5">
            <div class="col-6 col-sm-4 mt-4 text-center">
              <a href="">
                <div class="client-box">
                  <img
                    src="/clients/rumahsoal.png"
                    alt=""
                    style="height: 80%"
                  />
                </div>
              </a>
            </div>
            <div class="col-6 col-sm-4 mt-4 text-center">
              <a href="">
                <div class="client-box">
                  <img src="/clients/soalpppk.png" alt="" style="height: 80%" />
                </div>
              </a>
            </div>
            <div class="col-6 col-sm-4 mt-4 text-center">
              <a href="">
                <div class="client-box">
                  <img src="/clients/faba.png" alt="" style="height: 80%" />
                </div>
              </a>
            </div>
            <div class="col-6 col-sm-4 mt-4 text-center">
              <a href="">
                <div class="client-box">
                  <img src="/clients/siva.png" alt="" style="width:90%" />
                </div>
              </a>
            </div>
            <div class="col-6 col-sm-4 mt-4 text-center">
              <a href="">
                <div class="client-box">
                  <img src="/clients/kinarya.jpeg" alt="" style="height: 80%" />
                </div>
              </a>
            </div>
          </div>
          <div class="row mt-5">
            <div class="col-12">
              <div class="banner-footer">
                Temukan cara baru untuk bekerja sama.
                <div class="mt-3">
                  <a href="" class="btn btn-outline-white">
                    Kontak sales
                    <img
                      src="/icons/arrow_right.svg"
                      alt=""
                      style="width: 14px"
                      class="ms-2"
                    />
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="footer mt-5 pt-3">
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-12 col-sm-8">
          <div class="row">
            <div class="col-12 text-center">
              <p>Copyright © 2022</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
