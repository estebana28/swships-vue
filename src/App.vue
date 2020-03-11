<template>
  <v-app>
    <SwHeader />
    <router-view />
    <SwFooter />
  </v-app>
</template>

<script>
import SwHeader from "./components/SwHeader";
import SwFooter from "./components/SwFooter";

export default {
  name: "App",

  components: {
    SwHeader,
    SwFooter
  },

  data: () => ({
    //
  })
};
</script>
