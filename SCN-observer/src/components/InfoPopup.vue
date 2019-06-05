<template>
  <div>
    <v-dialog v-model="dialog" width="500" >
      <template v-slot:activator="{ on }">
        <v-icon
          dark
          v-on="on"
        >info
        </v-icon>
      </template>
      <v-card>
      <v-card-title class="headline grey lighten-2" primary-title >
      Observer
      </v-card-title>
      <v-card-text>
          Outil de visualisation d'images tuilés.
          <v-divider></v-divider>
          <div>GREYC - CHPC | 2019</div>
      </v-card-text>
      </v-card>
    </v-dialog>
  </div>
</template>

<script>
export default {
  data () {
    return {
      dialog: false
    }
  },
  name: 'InfoPopup'
}
</script>

<style>

</style>
