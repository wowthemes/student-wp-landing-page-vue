<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#hero"><img src="./../assets/images/logo.png" /></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        <span class="navbar-toggler-icon"></span>
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
        <div class="menu-wrapper  align-items-center d-lg-flex">

              <div class="navbar-logo">
                <a class="navbar-brand" href="#">
                  <i class="icon-cap"></i>
                </a>
              </div>

              <ul class="navbar-nav mb-2 mb-lg-0">
                <li class="nav-item" v-for="nav in navs" :key="nav.url">
                  <a class="nav-link" aria-current="page" :href="nav.url">{{ nav.label }}</a>
                </li>
              </ul>
              <div class="d-flex ms-4">
              <a :href="support" target="_blank" class="btn btn-primary rounded-pill get-support text-white">Get Support</a>
            </div>
        </div>
        
        <div class="overlay-menu" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"></div>

      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'main-header',
  data() {
    return {
      support: process.env.VUE_APP_SUPPORT_URL,
      navs: [
        {url: '#hero', label: 'Home'},
        {url: '#demos', label: 'Demos'},
        {url: '#installation', label: 'Installation'},
        {url: '#features', label: 'Features'},
        {url: '#documentation', label: 'Documentation'},
      ]
    }
  }
}
</script>

<style lang="scss">
.navbar {
  .get-support {
    padding: 20px 50px;
  }
  .navbar-nav {
    a {
      color: #000;
      font-weight: 600;
      font-size: 1rem;
      padding-right: 18px !important;
      padding-left: 18px !important;
      text-transform: uppercase;
    }
  }
}
.navbar-toggler-icon {
    width: 25px !important;
    height: 2px !important;
    background-color: #fff;
    display: block !important;
    margin-top: 5px;
    margin-bottom: 5px;
}

.navbar-collapse {
    flex-basis: 100%;
    flex-grow: 1;
    align-items: center;    
}

#navbarSupportedContent {
    position: fixed;
    top: 0;
    left: 0;
    width:100% ;
    height: 100vh;
    transform: translateX(-100%);
    opacity: 0;
    visibility: hidden;
    transition: all 250ms ease-in;
    z-index: 1;
}

.menu-wrapper{
  width: calc(100% - 80px);
  background-color:#fff;
  padding: 30px 15px;
  position: absolute;
  height: 100%;
  z-index: 2;
}

.overlay-menu {
  position: absolute;
  inset: 0;
  background-color: rgba(0,0,0,0.5);
  z-index: 1;
}

.collapse.show {
  transform: translateX(0) !important;
  opacity: 1 !important;
  visibility: visible !important;
}

.collapse:not(.show) {
    opacity: 0 !important;
    visibility: hidden !important;
}

[class^=icon-] {
    display: inline-block;
    line-height: 1;
    background-repeat: no-repeat;
    background-position: center;
    background-size: contain;
    vertical-align: middle;
}

.icon-cap {
  background-image: url("../assets/images/icon/header-icon.png");
  height: 75px;
  width: 135px;
}


@media (min-width: 992px) {


  .icon-cap {
    display: none;
  }

  #navbarSupportedContent {
    position: static;
    width: 100%;
    height: 100%;
    transform: translateX(0);
    opacity: 1 !important;
    visibility: visible !important;
   
  }

  .menu-wrapper {
    width: auto;
    height: auto;
    position: static;
    background-color: transparent;
    padding: 0;
  }

  .overlay-menu {
    display: none;
  }
  .navbar-nav a {
    color: #fff !important;
  }


}




</style>