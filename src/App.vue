<template>
  <v-app>
    <v-app-bar app color="purple" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Sadaf"
          class="shrink mr-2"
          contain
          src="./assets/logo.png"
          transition="scale-transition"
          width="40"
        />

        <strong style="font-size:18px; margin-left:5px;"
          >Happy Birthday Sadaf</strong
        >
      </div>
    </v-app-bar>

    <v-main>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default Vue.extend({
  name: "App",
  components: {
    HelloWorld
  }
});
</script>
