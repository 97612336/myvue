<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>123</h2>
    <a href="./vue01.vue">点我</a>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: '我的第一个vue页面！'
    }
  }
}
</script>
