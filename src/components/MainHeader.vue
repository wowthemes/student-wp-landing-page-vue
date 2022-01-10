<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#hero"><img src="./../assets/images/logo.png" /></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarSupportedContent">
        <ul class="navbar-nav mb-2 mb-lg-0">
          <li class="nav-item" v-for="nav in navs" :key="nav.url">
            <a class="nav-link" aria-current="page" :href="nav.url">{{ nav.label }}</a>
          </li>
        </ul>
        <div class="d-flex ms-4">
          <a href="#" class="btn btn-primary rounded-pill get-support text-white">Get Support</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'main-header',
  data() {
    return {
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
      color: #fff;
      font-weight: 600;
      font-size: 1rem;
      padding-right: 18px !important;
      padding-left: 18px !important;
      text-transform: uppercase;
    }
  }
}
</style>