<template>
  <div>
    <v-toolbar color="indigo" dark app clipped-left>
        <v-toolbar-title>{{title}}</v-toolbar-title>
        <v-spacer></v-spacer>
        <InfoPopup></InfoPopup>
    </v-toolbar>
  </div>
</template>

<script>
import InfoPopup from './InfoPopup.vue'

export default {
  data: function () {
    return {
      title: 'Observer'
    }
  },
  name: 'TopBar',
  components: {
    InfoPopup
  }
}
</script>

<style>

</style>
