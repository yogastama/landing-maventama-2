<script setup>
import NavbarComponent from "@/components/medium/NavbarComponent.vue";
import FooterComponent from "@/components/medium/FooterComponent.vue";
</script>
<template>
  <NavbarComponent></NavbarComponent>
  <section class="about">
    <div class="container-fluid">
      <div class="row justify-content-center">
        <div class="col-12 col-sm-8">
          <div class="row">
            <div class="col-12">
              <h2>Portofolio</h2>
              <p style="font-weight: 300">Build solution from Zero to One.</p>
              <img
                class="mt-4"
                src="/images/3box.png"
                alt="3box"
                style="width: 100px"
              />
            </div>
          </div>
          <div class="row mt-5 justify-content-center">
            <div class="col-12 col-sm-12 col-md-6 col-lg-4 mt-4">
              <div class="card" style="width: 100%">
                <div style="min-height: 180px">
                  <img
                    src="/apps/siva-app.png"
                    class="card-img-top"
                    alt="..."
                  />
                </div>
                <div class="card-body" style="height: 250px">
                  <h5 class="card-title text-dark">Siva</h5>
                  <p class="card-text text-dark" style="font-weight: 300">
                    Siva adalah aplikasi milik BPSDMI kemenperin yang berfungsi
                    untuk mengelola data kegiatan BPSDMI. Data statistik pada
                    fitur ini sangat penting.
                  </p>
                  <a
                    href="https://siva.kemenperin.go.id"
                    target="_blank"
                    class="btn btn-primary btn-blue"
                    >Kunjungi<img
                      src="/icons/arrow_right.svg"
                      alt=""
                      style="width: 14px"
                      class="ms-2"
                  /></a>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-12 col-md-6 col-lg-4 mt-4">
              <div class="card" style="width: 100%">
                <div style="min-height: 180px">
                  <img
                    src="/apps/rumahsoal-app.png"
                    class="card-img-top"
                    alt="..."
                  />
                </div>
                <div class="card-body" style="height: 250px">
                  <h5 class="card-title text-dark">RumahSoal</h5>
                  <p class="card-text text-dark" style="font-weight: 300">
                    RumahSoal adalah platform pembelajaran para calon PNS.
                    RumahSoal menyediakan pembelajaran Try Out SKB, SKD, dan
                    PPPK.
                  </p>
                  <a
                    href="https://rumahsoal.id"
                    target="_blank"
                    class="btn btn-primary btn-blue"
                    >Kunjungi<img
                      src="/icons/arrow_right.svg"
                      alt=""
                      style="width: 14px"
                      class="ms-2"
                  /></a>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-12 col-md-6 col-lg-4 mt-4">
              <div class="card" style="width: 100%">
                <div style="min-height: 180px">
                  <img
                    src="/apps/soalpppk-app.png"
                    class="card-img-top"
                    alt="..."
                  />
                </div>
                <div class="card-body" style="height: 250px">
                  <h5 class="card-title text-dark">SoalPPPK</h5>
                  <p class="card-text text-dark" style="font-weight: 300">
                    SoalPPPK adalah tempat pembelajaran PPPK untuk para calon
                    PNS. Platform ini baru saja launching 2022. Kami
                    menyelesaikannya dalam 2 bulan!
                  </p>
                  <a
                    href="https://soalpppk.id"
                    target="_blank"
                    class="btn btn-primary btn-blue"
                    >Kunjungi<img
                      src="/icons/arrow_right.svg"
                      alt=""
                      style="width: 14px"
                      class="ms-2"
                  /></a>
                </div>
              </div>
            </div>

            <div class="col-12 col-sm-12 col-md-6 col-lg-4 mt-4">
              <div class="card" style="width: 100%">
                <div style="min-height: 180px">
                  <img
                    src="/apps/kinarya-app.png"
                    class="card-img-top"
                    alt="..."
                  />
                </div>
                <div class="card-body" style="height: 250px">
                  <h5 class="card-title text-dark">Kinarya</h5>
                  <p class="card-text text-dark" style="font-weight: 300">
                    Aplikasi website ini adalah aplikasi validasi tiket yang
                    dibeli dari Blibli.com kemudian Kinarya dapat melakukan scan
                    tiket tersebut.
                  </p>
                  <a
                    href="https://kinaryaticket.com"
                    target="_blank"
                    class="btn btn-primary btn-blue"
                    >Kunjungi<img
                      src="/icons/arrow_right.svg"
                      alt=""
                      style="width: 14px"
                      class="ms-2"
                  /></a>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-12 col-md-6 col-lg-4 mt-4">
              <div class="card" style="width: 100%">
                <div style="min-height: 180px">
                  <img
                    src="/apps/cdc.png"
                    class="card-img-top"
                    alt="..."
                  />
                </div>
                <div class="card-body" style="height: 250px">
                  <h5 class="card-title text-dark">CDC</h5>
                  <p class="card-text text-dark" style="font-weight: 300">
                    Kami membantu CDC kemenperin dalam membuat sebuah form dengan fleksibel bergantung kepada input yang dimasukkan oleh user.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="banner-footer mt-5">
    <div class="container-fluid">
      <div class="row mt-5">
        <div class="col-12">
          <div class="banner-footer">
            Temukan cara baru untuk bekerja sama.
            <div class="mt-3">
              <a href="https://wa.me/6285158513669?text=Halo MavenTama, kami ingin melakukan diskusi" class="btn btn-outline-white">
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
  </section>
  <FooterComponent></FooterComponent>
</template>
