<template>
<div class="olddirver">
  <img src="./assets/a.jpg" />
  <h1>我在这里</h1>
  <router-View/>
  <song />
  <change/>
  <hidden/>
  <upperWord/>
</div>
</template>
<script>
import Song from './components/Song.vue'
import Change from './components/Change.vue'
import Hidden from './components/Hidden.vue'
import UpperWord from './components/UpperWord.vue'
export default {
  name: 'olddirver',
  components: {
    Song,
    Change,
    Hidden,
    UpperWord
  }
}
</script>
<style >
#olddriver {
  color: rgb(17, 44, 196);
  align-self: auto;
}
</style>
