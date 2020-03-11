<template>
  <v-app-bar app class="black">
    <v-container>
      <v-row align="center">
        <v-col cols="2">
          <v-img src="./../assets/logo.jpg" height="55" contain></v-img>
        </v-col>
        <v-col cols="6"></v-col>
        <v-col cols="4" justify="end">
          <router-link to="/">
            <v-btn class="white--text black">Home</v-btn>
          </router-link>
          <router-link to="/Ships">
            <v-btn class="white--text black">Ships</v-btn>
          </router-link>
          <router-link to="/About">
            <v-btn class="white--text black">About</v-btn>
          </router-link>
        </v-col>
      </v-row>
    </v-container>
  </v-app-bar>
</template>

<script></script>

<style>
a {
  text-decoration: none;
  font-family: "Orbitron", sans-serif;
}
</style>
