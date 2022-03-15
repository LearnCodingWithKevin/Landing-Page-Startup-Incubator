<template>
  <section id="footer">
    <div class="container px-0">
      <div class="row boder-bottom">
        <div class="col-lg-3 pl-0">
          <div class="footer-logo">
            <a href="#">kevin<span style="color: #0ec9ac">'s</span></a>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="footer-menu">
            <ul>
              <li><router-link to="/">Home</router-link></li>
              <li><a href="#info-panel">Features</a></li>
              <li><a href="#trusted-company">Trusted Company</a></li>
              <li><a href="#welcome-kevins">Welcome</a></li>
              <li><a href="#why-choose-right">Why Choose Us</a></li>
              <li><a href="#service">Program</a></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-3 text-right">
          <div class="footer-icon">
            <a href=""><i class="fa-brands fa-facebook-f" style="color: white; background: #0ac9ac; padding: 7px; border-radius: 5px; margin-left: 14px"></i></a>
            <a href=""><i class="fa-brands fa-twitter" style="color: white; background: #0ac9ac; padding: 7px; border-radius: 5px; margin-left: 14px"></i></a>
            <a href=""><i class="fa-brands fa-instagram" style="color: white; background: #0ac9ac; padding: 7px; border-radius: 5px; margin-left: 14px"></i></a>
            <a href=""><i class="fa-brands fa-youtube" style="color: white; background: #0ac9ac; padding: 7px; border-radius: 5px; margin-left: 14px"></i></a>
          </div>
        </div>
      </div>

      <div class="row mt-4">
        <div class="col-lg-7">
          <ul class="footer-details-menu">
            <li><a href="#">Privacy &amp; Policy</a></li>
            <li><a href="#">Terms Condition</a></li>
          </ul>
        </div>
        <div class="col-lg-5 text-right">
          <p class="copyright">Designed By <span style="color: #0ec9ac">Kevin Praditya</span> | &copy; 2022 All rights reserved</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Footer',
};
</script>
