<template>
  <v-app>

    <v-content>
      <router-view/>
    </v-content>

    <v-footer :fixed="fixed" app>
      <v-spacer></v-spacer>
      <span>Gemma is great</span>
      <v-spacer></v-spacer>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'App'
}
</script>
