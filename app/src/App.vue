<template>
  <v-app id="inspire">
    <v-app-bar app>
      <v-toolbar-title>Application</v-toolbar-title>
    </v-app-bar>

    <v-main class="grey lighten-3">
      <v-container class="pa-7">
        <v-row>
          <v-col>
            <v-card elevation="2" class="rounded-lg">
              <v-card-title>대방</v-card-title>
              <v-card-text>
                5분후 도착
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col>
            <v-card elevation="2" class="rounded-lg">
              <v-card-title>공군호텔</v-card-title>
              <v-card-text>
                5분후 도착a
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
        <v-row>
          <v-col>
            <v-card elevation="2" class="rounded-lg">
              <v-card-title>보라매</v-card-title>
              <v-card-text>
                5분후 도착
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  components: {
  },
  data: () => ({
  }),
}
</script>

<style>
.station_name {
}
</style>