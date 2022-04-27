<template>
  <div id="app">
    <div>
      <b-navbar toggleable="lg" type="light" variant="white" style="border: 2px solid black">
        <router-link to="/"><b-navbar-brand>ALDY'S PORTFOLIO</b-navbar-brand></router-link>

        <b-navbar-toggle target="nav-collapse" style="border: 2px solid black"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item class="navbar-item" disabled></b-nav-item>
            <b-nav-item class="navbar-item"><router-link to="/">HOME</router-link></b-nav-item>
            <b-nav-item class="navbar-item"><router-link to="/about">ABOUT</router-link></b-nav-item>
            <b-nav-item class="navbar-item"><router-link to="/portfolio">PORTFOLIO</router-link></b-nav-item>
            <b-nav-item class="navbar-item"><router-link to="/contact">CONTACT</router-link></b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <router-view v-slot="{ Component }">
      <transition name="fade">
        <component :is="Component" />
      </transition>
    </router-view>

    <!-- Footer -->
    <footer>
      <div class="text-center text-dark p-2" style="background-color: #fff; border: 2px solid black">
        © 2020 Copyright -
        <a class="text-dark" href="https://www.linkedin.com/in/aldyfikhrimuhammad/" target="_blank">Aldy Fikhri Muhammad</a>
      </div>
    </footer>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap");

#app {
  font-family: "Montserrat", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

.navbar-item {
  border-right: 2px solid black;
  padding: 5px;
}

nav a.router-link-exact-active {
  color: #000;
  text-decoration: none;
  text-shadow: 0 0 0.2rem #555;
}

nav a:hover {
  color: #000;
  text-shadow: 0 0 0.2rem #555;
  text-decoration: none;
  transition: 0.5s;
  transform: scale(1.1);
}
</style>
