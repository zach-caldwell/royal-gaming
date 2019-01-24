<template>
  <header class="header_area">
    <div class="main_menu">
      <b-navbar class="navbar-expand-lg navbar-light">
        <div class="container">
          <!-- Brand and toggle get grouped for better mobile display -->
          <nuxt-link to="/" class="navbar-brand logo_h">
            <img src="~/assets/img/website-logo1.png" alt>
          </nuxt-link>
          <b-navbar-toggle
            type="button"
            data-toggle="collapse"
            target="navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </b-navbar-toggle>
          <!-- Collect the nav links, forms, and other content for toggling -->
          <b-collapse is-nav class="offset" id="navbarSupportedContent">
            <b-navbar-nav class="nav menu_nav justify-content-center">
              <nuxt-link tag="li" to="/" class="nav-item" exact>
                <a class="nav-link">Home</a>
              </nuxt-link>
              <nuxt-link tag="li" to="/about" class="nav-item">
                <a class="nav-link">About</a>
              </nuxt-link>
              <nuxt-link tag="li" to="/gallery" class="nav-item">
                <a class="nav-link">Gallery</a>
              </nuxt-link>
              <nuxt-link tag="li" to="/blog" class="nav-item">
                <a class="nav-link">Blog</a>
              </nuxt-link>
            </b-navbar-nav>
            <ul class="nav navbar-nav navbar-right">
              <li class="nav-item">
                <a href="https://discord.gg/AWqfvY3" target="_blank" class="primary_btn">
                  join us
                  <span class="fab fa-discord"></span>
                </a>
              </li>
            </ul>
          </b-collapse>
        </div>
      </b-navbar>
    </div>
  </header>
</template>

