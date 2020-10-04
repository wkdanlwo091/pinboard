<template>
  <div id="app">
      <Mobile></Mobile>
      <Search></Search>
      <Login></Login>
      <List></List>
  </div>
</template>

<script>
import List from "./components/List.vue";
import Login from "./components/Login.vue";
import Search from "./components/Search.vue";
import Mobile from "./components/Mobile.vue";

export default {
  components: {
    List: List,
    Login: Login,
    Search: Search,
    Mobile: Mobile,
  },
}
</script>

<style>
</style>
