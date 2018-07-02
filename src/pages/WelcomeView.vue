<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <img src="/static/v.png" alt="Vuetify.js" class="mb-5" />
      </div>
      <v-card>
        <v-card-text>
          <p>Welcome to the best SSR template ever!</p>
          <p>This boilerplate has pre configured SSR, server caching, wp basic calls already done for you!</p>
        </v-card-text>
        <v-card-actions>
          <v-btn color="primary" flat router to="/inspire">Continue</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>
