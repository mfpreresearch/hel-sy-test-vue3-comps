<template>
  <div class="hello">
    <h1>{{ name }}</h1>
    <div class="description">
      我是远程 App2 组件
    </div>
  </div>
</template>

<script>
export default {
  name: 'App2',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
