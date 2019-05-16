<template>
  <div id="observer">
    <LeftDrawer>
    </LeftDrawer>
    <TopBar>
    </TopBar>
  </div>
</template>

<script>
import TopBar from './TopBar.vue'
import LeftDrawer from './LeftDrawer'

export default {
  components: {
    TopBar,
    LeftDrawer
  },
  name: 'Dashboard'
}
</script>

<style>

</style>
