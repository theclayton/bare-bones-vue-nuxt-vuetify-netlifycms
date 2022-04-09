<template>
  <div>
    <v-app-bar color="deep-grey accent-4" dense dark>
      <v-toolbar-title>{{ title }}</v-toolbar-title>

      <v-spacer></v-spacer>

      <NuxtLink to="/"><v-btn class="blue--text">Home</v-btn></NuxtLink>

      <NuxtLink to="/about"><v-btn class="blue--text">About</v-btn></NuxtLink>
    </v-app-bar>
  </div>
</template>

<script>
import content from "../content/header";

export default {
  data() {
    return content;
  },
};
</script>