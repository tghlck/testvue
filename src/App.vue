<template>
  <v-app>
    <v-content>
     <layoutDrawer/>
      <Login />
     
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import layoutDrawer from "./layout/layoutDrawer";
import Login from "./components/loginForm";

export default {
  name: "App",

  components: {
    layoutDrawer,
    Login
  },

  data: () => ({
    drawer: null
  })
};
</script>


