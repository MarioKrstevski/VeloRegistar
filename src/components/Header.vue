<template>
 <nav>
     <div id="logo">
         <a href="#home"><img src="../assets/logo.png" alt="Logo"></a>
     </div>
     <ul>
         <li><a href="#our-team">Our Team</a></li>
         <li><a href="#mission">Mission</a></li>
         <li><a href="#support">Support</a></li>
         <li><a href="#contact">Contact</a></li>
     </ul>
 </nav>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#logo {
  display: inline-block;
  margin-left: 50px;
}
#logo img {
  width: 100px;
  height: 100px;
}
nav {
  height: 100px;
  width: 100%;
  background-color: #f8f9fb;
}
ul {
  float: right;
  padding-right: 50px;
  display: inline-block;
  margin: 0;
}
ul li {
  list-style-type: none;
  display: inline;
  padding: 0px 15px;
  line-height: 100px;
}
ul li a {
  color: rgb(58, 58, 58);
}
ul li a:hover {
  color: rgb(139, 139, 255);
}
</style>
