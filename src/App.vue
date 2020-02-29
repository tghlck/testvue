<template>
  <v-app>
    <v-content>
      <Baseline/>
    </v-content>
  </v-app>
</template>

<script>
import Baseline from './components/baseline-template';

export default {
  name: 'App',

  components: {
    Baseline
  },

  data: () => ({
    //
  }),
};
</script>
