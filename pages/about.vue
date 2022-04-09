<template>
  <v-container>
    <v-card>
      <v-card-title class="headline"> {{ heading }} </v-card-title>
    </v-card>
  </v-container>
</template>

<script>
import content from "../content/about";

export default {
  head() {
    // Set Meta Tags for this Page
  },
  data() {
    return content;
  },
};
</script>
