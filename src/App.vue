<template>
  <v-app>
    <v-content>
      <headBarDrawer />
      <Login />
      <footBar />
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import footBar from "./layout/footBar";
import headBarDrawer from "./layout/headBarDrawer";
import Login from "./components/loginForm";

export default {
  name: "App",

  components: {
    footBar,
    headBarDrawer,
    Login
  },

  data: () => ({
    drawer: null
  })
};
</script>


