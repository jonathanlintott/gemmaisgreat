<template>
  <v-container fluid>
    <v-slide-y-transition mode="out-in">
      <v-layout column align-center>
        <br/><br/>
        <h2>Is Gemma Great?</h2>
        <div>
          <v-btn @click="message ='You are right!'">Yes</v-btn>
          <v-btn @click="message = 'Fool! You could not be more wrong'">No</v-btn>
        </div>
        <hr/>
        <br/><br/><br/>
        <h1>{{ message }}</h1>
      </v-layout>
    </v-slide-y-transition>
  </v-container>
</template>

<script>
export default {
  data () {
    return {
      message: ''
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
