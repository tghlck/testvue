<template>
  <v-container>
    <v-layout>
      <v-flex justify-center>
         <v-container fluid>
       <pDash />
    
  
  </v-container> 
    
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import pDash from "../components/providerDashboard";
// @ is an alias to /src

export default {
  name: "App",
  components: {
    pDash
  },
}
</script>
