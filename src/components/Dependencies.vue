<template>
  <div class="hello">
    <h2>Dependencies</h2>
    <ul>
      <li>
        bootstrap
      </li>
      <li>
        bootstrap-vue
      </li>
      <li>
        jquery
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
}
</style>
