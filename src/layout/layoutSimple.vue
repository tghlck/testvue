<template>
 <div>
   
    <v-app-bar
      app
      color="indigo"
      dark
    >

      <v-toolbar-title>Balance</v-toolbar-title>
    </v-app-bar>

    <v-footer
      color="indigo"
      app
    >
      <span class="white--text">Balance &copy; 2020</span>
    </v-footer>
 </div>
</template>

<script>


  export default {
    
    props: {
      source: String,
    },
    data: () => ({
    }),
  }
</script>