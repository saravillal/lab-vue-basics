<template>
  <div class="home">
    <NavBar></NavBar>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <FooterMenu></FooterMenu>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import NavBar from '../components/NavBar.vue';
import FooterMenu from '../components/FooterMenu.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    NavBar,
    FooterMenu,
  },
};
</script>
