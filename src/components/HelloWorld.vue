<template>
  <v-app>
    <v-dialog v-model="modal">
      <v-card>
        edsf
        <v-icon>create</v-icon>
      </v-card>
    </v-dialog>
  </v-app>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data() {
      return {
        modal:true,
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
