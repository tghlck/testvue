<template>
  <v-app>
    <v-content>
      <Baseline/>
      <Centered/>
    </v-content>
  </v-app>
</template>

<script>
import Baseline from './components/baseline-template';
import Centered from './components/centered-template';

export default {
  name: 'App',

  components: {
    Baseline,
    Centered
  },

  data: () => ({
    //
  }),
};
</script>
