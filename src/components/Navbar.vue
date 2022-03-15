<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container">
      <a class="navbar-brand" href="#">kevin<span style="color: #0ec9ac">'s</span></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <router-link class="nav-link active" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#info-panel">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#trusted-company">Trusted Company</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#welcome-kevins">Welcome</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#why-choose-right">Why Choose Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#service">Program</a>
          </li>
        </ul>

        <div class="d-flex header-btn">
          <a href="#get-free">Join Us</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>
