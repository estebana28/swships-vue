<template>
  <v-app>
    <v-app-bar height="10%">
      <SwHeader />
    </v-app-bar>
    <v-content>
    </v-content>
  </v-app>
</template>

<script>
import SwHeader from "./components/SwHeader";

export default {
  name: "App",

  components: {
    SwHeader
  },

  data: () => ({
    //
  })
};
</script>
