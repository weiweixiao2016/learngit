<template>
  <div class="MyWorld">
    <h1>{{msg}}</h1>
    <song/>
  </div>
</template>
<script>
import Song from './Song.vue'
export default {
  name: 'MyWorld',
  data () {
    return {
      msg: '逮虾户'
    }
  },
  components: {
    Song
  }
}
</script>
<style scoped>
h1 {
  color: rgb(205, 43, 226);
}
</style>
