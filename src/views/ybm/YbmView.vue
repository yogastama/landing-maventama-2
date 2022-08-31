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
              <h2>Yoga Bagas Menulis</h2>
              <p style="font-weight: 300">Penulis e-book.</p>
              <img
                class="mt-4"
                src="/images/3box.png"
                alt="3box"
                style="width: 100px"
              />
            </div>
            <div class="row mt-5">
              <div class="col-12">
                <p>Berikut adalah katalog Yoga Bagas Menulis.</p>
              </div>
              <div class="col-12 col-md-4">
                <div class="card">
                  <div class="card-body">
                    <img src="/banner.png" alt="banner" width="100%" />
                  </div>
                  <div class="card-footer">
                    <div class="d-grid gap-2">
                      <a
                        href="https://bukuprp.com"
                        class="btn btn-primary"
                        target="_blank"
                      >
                        Beli Buku Perspektif Relatif Perspektif
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <FooterComponent></FooterComponent>
</template>
