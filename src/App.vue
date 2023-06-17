<template>
  <Navbar />
  <div class="container py-4">
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
