<template>
  <div class="fixed-top">
    <div class="navbar-top">
      <div class="container-fluid">
        <div class="row justify-content-center">
          <div class="col-12 col-sm-10">
            <div class="row">
              <div class="col-4 col-sm-4 pt-2">
                <router-link to="/">
                  <img src="/images/logo.png" alt="logo" style="width: 200px" />
                </router-link>
              </div>
              <div class="col-8 col-sm-8">
                <div class="list-menu-navbar text-end d-block d-md-none">
                  <a
                    class="dropdown-toggle"
                    href="#"
                    role="button"
                    data-bs-toggle="dropdown"
                    aria-expanded="false"
                  >
                    Menu
                  </a>

                  <ul class="dropdown-menu">
                    <li><router-link class="dropdown-item text-dark" to="/">Beranda</router-link></li>
                    <li>
                      <router-link class="dropdown-item text-dark" to="/about">Tentang</router-link>
                    </li>
                    <li>
                      <router-link class="dropdown-item text-dark" to="/portfolio">Portofolio</router-link>
                    </li>
                    <li>
                      <router-link class="dropdown-item text-dark" to="/yogabagas-menulis">Yoga Bagas Menulis</router-link>
                    </li>
                  </ul>
                </div>
                <div class="list-menu-navbar text-end d-none d-md-block">
                  <router-link to="/"> Beranda </router-link>
                  <router-link to="/about"> Tentang </router-link>
                  <router-link to="/portfolio"> Portofolio </router-link>
                  <router-link to="/yogabagas-menulis"> Yoga Bagas Menulis </router-link>
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
