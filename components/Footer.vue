<template>
  <footer class="footer_area section_gap_top">
    <div class="container">
      <div class="row single-footer-widget">
        <div class="col-lg-6 col-md-6 col-sm-12">
          <div class="copy_right_text">
            <p>
              Copyright &copy; {{ getYear }} All rights reserved
              <br>UI template courtesy of
              <a href="https://colorlib.com" target="_blank">Colorlib</a>
            </p>
          </div>
        </div>
        <div class="col-lg-6 col-md-6 col-sm-12">
          <div class="social_widget">
            <a href="#">
              <i class="fab fa-discord"></i>
            </a>
            <a href="#">
              <i class="fab fa-twitch"></i>
            </a>
            <a href="#">
              <i class="fab fa-youtube"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  computed: {
    getYear: function currentYear() {
      return new Date().getFullYear();
    }
  }
};
</script>

