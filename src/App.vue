<template>
  <v-app>
    <v-content>
      <v-container>
        <v-row>
          <Pomodoro />
        </v-row>
       </v-container>
    </v-content>
  </v-app>
</template>

<script>
import Pomodoro from './components/Pomodoro.vue'

export default {
  name: 'App',

  components: {
    Pomodoro,
  },

  data: () => ({
    //
  }),
};
</script>
