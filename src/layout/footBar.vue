<template>
 <div>
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
      drawer: null,
    }),
  }
</script>