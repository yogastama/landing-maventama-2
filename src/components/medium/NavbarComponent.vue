<template>
  <div class="fixed-top">
    <div class="navbar-top">
      <div class="container-fluid">
        <div class="row justify-content-center">
          <div class="col-12 col-sm-10">
            <div class="row">
              <div class="col-12 col-sm-4 pt-2">
                <img src="/images/logo.png" alt="logo" style="width: 200px" />
              </div>
              <div class="col-8 col-sm-8 d-none d-sm-block">
                <div class="list-menu-navbar text-end">
                  <router-link to="/"> Beranda </router-link>
                  <router-link to="/about"> Tentang </router-link>
                  <router-link to="/portfolio"> Portofolio </router-link>
                  <a
                    href="https://www.linkedin.com/company/76212922"
                    target="_blank"
                  >
                    <img
                      src="/images/linkedin.png"
                      alt="linkedn"
                      style="width: 20px"
                    />
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
