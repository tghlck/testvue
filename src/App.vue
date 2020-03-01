<template>
 <v-app>
    <v-navigation-drawer
      v-model="drawer"
      app
    >
      <v-list dense>
        <v-list-item to="/home">
          <v-list-item-action>
            <v-icon>mdi-home</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>Home</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item to="/contact">
          <v-list-item-action>
            <v-icon>mdi-mailbox-up</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>Contact</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item to="/login">
          <v-list-item-action>
            <v-icon>mdi-account</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title>Login</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-app-bar
      app
      color="indigo"
      dark
      
    >
      <v-app-bar-nav-icon @click.stop="drawer = !drawer" />
      <v-toolbar-title>Balance</v-toolbar-title>
    </v-app-bar>

  <v-content>
      <router-view></router-view>
    </v-content>
    
    <v-footer
      color="indigo"
      app
    >
      <span class="white--text">Balance &copy; 2020</span>
    </v-footer>
 </v-app>
</template>

<script>


  export default {
    name: "App",
    props: {
      source: String,
    },
    data: () => ({
      drawer: null,
    }),
  }
</script>



