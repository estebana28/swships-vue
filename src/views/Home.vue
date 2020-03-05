<template>
  <div>
    <router-view />
    <SwHeader />
    <div class="home">
      <img alt="Vue logo" src="../assets/logo.png" />
      <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import SwHeader from "@/components/SwHeader.vue";

export default {
  name: "Home",
  components: {
    SwHeader
  }
};
</script>
