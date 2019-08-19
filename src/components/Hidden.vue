<template>
  <div class="hidden">
    <label for="r2" />勾选显示隐藏
    <input type="checkbox" v-model="value" id="r2" />
    <p id="hiddenone" v-if="value">现在你看到我了</p>
  </div>
</template>
<script>
export default {
  name: 'hidden',
  data () {
    return {
      value: false
    }
  }
}
</script>
