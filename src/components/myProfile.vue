<template>
  <v-container fill-height fluid grid-list-xl>
        
        <v-row>
        <v-subheader>
          <div class="headline">My Profile</div>

        </v-subheader>
      </v-row>

    <v-layout justify-center wrap>
      <v-flex xs12 md8>
        <material-card color="indigo" title="Edit Profile" text="Complete your profile">
          <v-card>
            <v-container py-0>
              <v-layout wrap>
               
                <v-flex xs12 md6>
                  <v-text-field label="First Name" class="purple-input" />
                </v-flex>
                <v-flex xs12 md6>
                  <v-text-field label="Last Name" class="purple-input" />
                </v-flex>
                <v-flex xs12 md12>
                  <v-text-field label="Adress" class="purple-input" />
                </v-flex>
                <v-flex xs12 md4>
                  <v-text-field label="City" class="purple-input" />
                </v-flex>
                <v-flex xs12 md4>
                  <v-text-field label="Country" class="purple-input" />
                </v-flex>
                <v-flex xs12 md4>
                  <v-text-field class="purple-input" label="Postal Code" type="number" />
                </v-flex>
                <v-flex xs12 text-xs-right>
                  <v-btn class="mx-0 font-weight-light" dark color="indigo">Edit Profile</v-btn>
                </v-flex>
              </v-layout>
            </v-container>
          </v-card>
        </material-card>
      </v-flex>
      <v-flex xs12 md4>
        <material-card class="v-card-profile">
          <v-avatar slot="offset" class="mx-auto d-block" size="130">
            <img src="https://demos.creative-tim.com/vue-material-dashboard/img/marc.aba54d65.jpg" />
          </v-avatar>
          <v-card-text class="text-xs-center">
            <h6 class="category text-gray font-weight-thin mb-3">Sample Text</h6>
            <h4 class="card-title font-weight-light">John Doe</h4>
            <p
              class="card-description font-weight-light"
            >SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT SAMPLE TEXT </p>
          </v-card-text>
        </material-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  props: {
    source: String
  }
};
</script>