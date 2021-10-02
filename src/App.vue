<template>
  <div id="app">
    <Header/>
    <NavigationDesktop/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import NavigationDesktop from "@/components/NavigationDesktop";

export default {
  name: 'App',
  components: {
    Header,
    NavigationDesktop
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
