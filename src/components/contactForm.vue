<template>
 <div>
    <v-container fluid>

       <v-row justify="center">
        <v-col cols="6">

            <v-card
            justify="center">
              <v-toolbar
                color="indigo"
                dark
                
              >
                <v-toolbar-title>Contact Us!</v-toolbar-title>
                <v-spacer />
              </v-toolbar>
              <v-card-text>
                <form> 
        
    <v-text-field
      v-model="name"
      :error-messages="nameErrors"
      label="Name"
      required
      @input="$v.name.$touch()"
      @blur="$v.name.$touch()"
    ></v-text-field>
    <v-text-field
      v-model="email"
      :error-messages="emailErrors"
      label="E-mail"
      required
      @input="$v.email.$touch()"
      @blur="$v.email.$touch()"
    ></v-text-field>
    
       <v-textarea 
  
      v-model="message"
      label="Message"
      required
      @input="$v.name.$touch()"
      @blur="$v.name.$touch()"
    ></v-textarea>

    <v-btn @click="submit">Send</v-btn>
  </form>
              </v-card-text>
            </v-card>
        </v-col>
       </v-row>
    </v-container>
 </div>
</template>

<script>
  export default {
    props: {
      source: String,
    },
  }
</script>

<script>
  export default {
    props: {
      source: String,
    },
  }
</script>