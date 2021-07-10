<template>
  <v-app style="background: #EF5350;">
    <v-main>
      <v-container>
        <v-row justify="center">
          <v-col sm="6" >
            <Pomodoro/>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Pomodoro from './components/Pomodoro.vue';

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
