<template>
  <v-navigation-drawer
    fixed
    v-model="drawer"
    app
    clipped
  >
    <v-list>
      <v-list-tile>
        <v-list-tile-content>
          <v-list-tile-title>{{Over}}</v-list-tile-title>
        </v-list-tile-content>
      </v-list-tile>
      <v-divider></v-divider>
      <v-list-tile>
        <v-list-tile-content>
          <v-list-tile-title>{{Sshot}}</v-list-tile-title>
        </v-list-tile-content>
      </v-list-tile>
    </v-list>
  </v-navigation-drawer>
</template>

<script>
export default {
  data: function () {
    return {
      Over: 'Ouvrir une image',
      Sshot: "Capture d'écran"

    }
  },
  name: 'LeftDrawer'
}
</script>

<style>

</style>
