<template>
  <div class="upperword">
    <label for="r3" />输入获得首字母大写加成
    <input v-model="message" />
    获得结果:
    <div id="result">{{message|capitalize}}</div>
  </div>
</template>
<script>
export default {
  name: 'upperword',
  data () {
    return {
      message: 'run'
    }
  },
  filters: {
    capitalize: function (value) {
      if (!value) return ''
      value = value.toString()
      return ' ' + value.charAt(0).toUpperCase() + value.slice(1) + '看到了吗'
    }
  }
}
</script>
