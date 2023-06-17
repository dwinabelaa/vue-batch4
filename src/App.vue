<template>
  <!-- <nav class="navbar navbar-expand-lg bg-danger">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Belajar Vue Js</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link class="nav-link active" aria-current="page" :to="{ name: 'home' }" href="#">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link active" href="#" :to="{ name: 'about' }">About</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" href="#" :to="{ name: 'contact' }">Contact</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled">Disabled</a>
          </li>
        </ul>
      </div>
    </div>
  </nav> -->
  <div class="container py-4">
    <Navbar />
    <router-view></router-view>
  </div>
</template>

<script>
import Home from './views/Home.vue'
import Navbar from './components/Navbar.vue'

export default {
  components: {
    Home,
    Navbar,
  },
};
</script>
