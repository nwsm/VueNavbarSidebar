<template>
  <div class="p-3 mb-2 bg-secondary text-white" id="menu">
    <ul>
      <li v-for="route in this.$router.options.routes">
        <router-link :to="route.path" class="text-white">{{route.name}}</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {

}
</script>

<style>
#menu {
  float: left;
  height: 100vh;
  text-align: left;
  width: 25%;
  max-width: 15em;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
</style>
