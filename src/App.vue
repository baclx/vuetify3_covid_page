<template>
  <v-app>
    <v-main>
      <CovidGov/>
    </v-main>
  </v-app>
</template>

<script>
import CovidGov from './components/CovidGov.vue'

export default {
  name: 'App',

  components: {
    CovidGov,
  },

  data: () => ({
    //
  }),
}
</script>
