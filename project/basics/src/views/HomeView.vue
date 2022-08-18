<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <BodyText></BodyText>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import BodyText from '../components/BodyText.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    BodyText,
  },
};
</script>
