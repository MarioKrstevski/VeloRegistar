<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <img :src="url" alt="TEST SLIKA" height="300" width="200">
    
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  data() {
    return {
      url: require("../assets/ivona-resized.png") // eslint-disable-line no-undef
    };
  }
};
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
