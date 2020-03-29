<template>
  <v-app :style="{background: $vuetify.theme.themes['dark'].background}">
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>
