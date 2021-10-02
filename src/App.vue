<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>
import Header from "@/components/Header";

export default {
  name: 'App',
  components: {
    Header,
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
