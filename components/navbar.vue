<template>
  <div>
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.15.4/css/all.css"
      integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm"
      crossorigin="anonymous"
    />

    <nav class="fixed-top d-flex justify-content-between">
      <div>
        <b-navbar toggleable="lg" type="dark">
          <b-navbar-brand>
            <router-link to="/" class="navbar-brand mt-2">
              <img src="../images/vehica-logo-white-retina.png" alt="" />
            </router-link>
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
              <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
                <li class="nav-item dropdown">
                  <a
                    class="nav-link dropdown-toggle text-white"
                    href="#"
                    id="dropdownId"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                    >Home</a
                  >
                  <div
                    class="dropdown-menu py-2 px-3"
                    aria-labelledby="dropdownId"
                  >
                    <router-link to="/" class="dropdown-item"
                      >Homepage Mosaic</router-link
                    >
                    <hr class="my-1" />
                    <div class="divider"></div>
                    <nuxt-link to="/" class="dropdown-item"
                      >Homepage Car Dealer</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Homepage Location
                    </nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Homepage Moderm</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Homepage Classic</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Homepage Slideshow</nuxt-link
                    >
                  </div>
                </li>

                <li class="nav-item dropdown">
                  <a
                    class="nav-link dropdown-toggle text-white"
                    href="#"
                    id="dropdownId"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                    >Search</a
                  >
                  <div
                    class="dropdown-menu py-2 px-2"
                    aria-labelledby="dropdownId"
                  >
                    <nuxt-link to="/" class="dropdown-item"
                      >Classic-Rows</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Classic-Cards</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item">Map-Rows</nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Map-Cards</nuxt-link
                    >
                  </div>
                </li>
                <li class="nav-item dropdown">
                  <a
                    class="nav-link dropdown-toggle text-white"
                    href="#"
                    id="dropdownId"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                    >Listing</a
                  >
                  <div
                    class="dropdown-menu py-2 px-3"
                    aria-labelledby="dropdownId"
                  >
                    <nuxt-link to="/" class="dropdown-item">Gallery</nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item">Mosaic</nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item">Carousel</nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Private Message System</nuxt-link
                    >
                  </div>
                </li>
                <li class="nav-item dropdown">
                  <a
                    class="nav-link dropdown-toggle text-white"
                    href="#"
                    id="dropdownId"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                    >Pages</a
                  >
                  <div
                    class="dropdown-menu py-2 px-2"
                    aria-labelledby="dropdownId"
                  >
                    <nuxt-link to="/" class="dropdown-item">About Us</nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item">Contact</nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Our team-simple</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Our team-advanced</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >User profiler page</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >User profiler page</nuxt-link
                    >
                    <hr class="my-1" />
                    <router-link to="/" class="dropdown-item">Sold</router-link>
                    <hr class="my-1" />
                    <router-link to="/" class="dropdown-item"
                      >Loan Calcultor</router-link
                    >
                    <hr class="my-1" />
                    <router-link to="/" class="dropdown-item">FAQ</router-link>
                    <hr class="my-1" />
                    <router-link to="/" class="dropdown-item"
                      >Login/Register</router-link
                    >
                    <hr class="my-1" />
                    <router-link to="/" class="dropdown-item"
                      >404 Page</router-link
                    >
                  </div>
                </li>

                <li class="nav-item dropdown">
                  <a
                    class="nav-link dropdown-toggle text-white"
                    href="#"
                    id="dropdownId"
                    data-toggle="dropdown"
                    aria-haspopup="true"
                    aria-expanded="false"
                    >More</a
                  >

                  <div
                    class="dropdown-menu py-2 px-3"
                    aria-labelledby="dropdownId"
                  >
                    <nuxt-link to="/" class="dropdown-item"
                      >Refund Policy(Guanrantee)</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Help Center (Support)</nuxt-link
                    >
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item">Reviews</nuxt-link>
                    <hr class="my-1" />
                    <nuxt-link to="/" class="dropdown-item"
                      >Need Real Estae Theme?</nuxt-link
                    >
                  </div>
                </li>
              </ul>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>

      <div>
        <b-navbar toggleable="lg" type="dark">
          <b-navbar-toggle target="nav-collapse1"></b-navbar-toggle>
          <b-collapse id="nav-collapse1" is-nav>
            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
              <div class="form-inline my-2 my-lg-0 text-white">
                <nuxt-link class="nav-link mx-2 text-white" to="/user/login">
                  <i class="far fa-user mr-1 login-i"></i>
                  Login</nuxt-link
                >
                |
                <nuxt-link class="nav-link mx-2 text-white" to="/user/register"
                  >Register</nuxt-link
                >
                <nuxt-link
                  to="/"
                  class="nav-link btn_add mx-3"
                  @click.prevent=""
                >
                  <i class="fas fa-plus mr-1"></i>
                  add listing
                </nuxt-link>
              </div>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </nav>
    <div>
      <nuxt-child />
    </div>
  </div>
</template>


<style scope>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.navbar {
  padding: 2px 25px;
  background: transparent;
}
.navbar-brand img {
  height: 25px;
}

.nav-item {
  margin: 0 10px;
  padding-top: 10px;
}
.nav-item:hover {
  /* background: rebeccapurple; */
  transition: 1s;
  border-top: 2px solid red;
}

.dropdown-item {
  padding: 0;
  margin: 2px 4px;
  background: none;
}
.dropdown-item:focus {
  background: none;
}
.dropdown-item:hover {
  color: red;
  background: none;
}
.login-i {
  color: #e84005;
}
.btn_add {
  padding: 7px 10px;
  background: transparent;
  border: 1px solid #e84005;
  color: white;
  cursor: pointer;
  border-radius: 5px;
}
.btn_add:hover {
  background: #e84005;
  border: none;
}
.menu-icon {
  color: #e84005;
}
@media all and (min-width: 480px) {
  .navbar .nav-item .dropdown-menu {
    display: none;
  }
  .navbar .nav-item:hover .dropdown-menu {
    display: block;
  }
  .navbar .nav-item .dropdown-menu {
    margin-top: 0;
  }
}
</style>