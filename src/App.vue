<template>
  <v-app>
    <v-container>
      <Converter/>
    </v-container>
  </v-app>
</template>

<script>
import Converter from "@/components/Converter";

export default {
  name: 'App',

  components: {
    Converter,
  },

  data: () => ({
    //
  }),
};
</script>


<style>
    v-app {
        display: flex;
        justify-content: center;
    }
</style>