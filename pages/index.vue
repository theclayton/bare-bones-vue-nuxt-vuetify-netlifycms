<template>
  <v-container>
    <v-card elevation="2" class="pa-4">
      <v-card-title class="headline">{{ heading }}</v-card-title>
      <v-card-text class="text-subtitle-1">{{ subheading }}</v-card-text>

      <v-divider></v-divider>

      <v-img
        max-width="200"
        :src="mainImage"
        class="mt-5 rounded-xl"
        :elevation="5"
      ></v-img>
    </v-card>
  </v-container>
</template>

<script>
import content from "../content/index";

export default {
  head() {
    // Set Meta Tags for this Page
  },
  data() {
    return content;
  },
};
</script>
