<template>
<NavBar></Navbar>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <FooterMenu></FooterMenu>
</template>

<script>
// @ is an alias to /src
import NavBar from '../components/NavBar.vue';
import FooterMenu from '../components/FooterMenu.vue';

export default {
  name: 'AboutView',
  components: {
    NavBar,
    FooterMenu,
  },
};
</script>
