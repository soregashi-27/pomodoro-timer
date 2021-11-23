<template>
<v-card class="mt-8">
  <v-tabs v-model="timerType">
    <v-tab
      v-for="tab in tabTitles"
      :key="tab"
    >
    {{ tab }}
    </v-tab>
  </v-tabs>
</v-card>
</template>

<script>
export default {
  data() {
    return{
      timerType: 0,
      tabTitles: ['Pomodoro', 'Short Break', 'Long Break']
    }
  }
}
</script>

<style lang="sass" scoped>
.v-card 
  width: 400px

</style>