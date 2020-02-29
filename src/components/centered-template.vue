<template>
 <div>
    <v-content>
        <v-row
          align="center"
          justify="center"
        >
          <v-col
            cols="12"
            sm="8"
            md="4"
          >
            <v-card>
              <v-toolbar
                color="indigo"
                dark
                flat
              >
                <v-toolbar-title>Login form</v-toolbar-title>
                <v-spacer />
              </v-toolbar>
              <v-card-text>
                <v-form>
                  <v-text-field
                    label="Login"
                    name="login"
                    type="text"
                  />

                  <v-text-field
                    id="password"
                    label="Password"
                    name="password"
                    type="password"
                  />
                </v-form>
              </v-card-text>
              <v-card-actions>
                <v-spacer />
                <v-btn color="indigo"
                dark
                >Login</v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
    </v-content>
 </div>
</template>

<script>
  export default {
    props: {
      source: String,
    },
  }
</script>