<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <h3>Vuetify Sandbox</h3>
      </div>
    </v-app-bar>

    <v-main>
      <SandBox/>
    </v-main>
  </v-app>
</template>

<script>
import SandBox from './components/SandBox';

export default {
  name: 'App',

  components: {
    SandBox,
  },
};
</script>
