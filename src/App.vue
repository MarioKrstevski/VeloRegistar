<template>
  <div id="app" class="">
    <Header msg="Zdravo"></Header>
    <Introduction  msg="Chao"></Introduction>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Introduction from "./components/Introduction.vue";

export default {
  name: "app",
  components: {
    Introduction,
    Header
  }
};
</script>

<style>
#app {
}
</style>
