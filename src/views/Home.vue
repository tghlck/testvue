<template>
  <v-container>
    <v-layout>
      <v-flex xs12 justify-center>
         <v-container fluid>
    <v-row>
      <v-col cols="12">
        <v-img src="../assets/Balance-2.png" contain max-height="200px"> </v-img>
      
      </v-col>

    </v-row>
    <v-row>
      <Test />
    </v-row>
  </v-container> 
    
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import Test from "../components/test";
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    Test
  
  }
}
</script>
