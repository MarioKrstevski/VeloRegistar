<template>
 <nav>
    <div class="navigation outside-container">
         <div id="logo">
            <a href="#home"><img src="../assets/widelogo2.png" alt="Logo"></a>
        </div>
        <ul>
            <li><a href="#mission">Нашата Цел</a></li>
            <!-- <li><a href="#support">Support</a></li> -->
            <li><a href="#our-team">Тимот</a></li>
            <li><a href="#contact">Контакт</a></li>
        </ul>
    </div>
 </nav>
</template>

<script>
export default {
  name: "Header"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#logo {
  display: inline-block;
  margin-left: 1%;
}
#logo img {
  margin: 15px;
  height: 90px;
}
nav {
  height: 100px;
  width: 100%;
  font-size: 20px;
  font-weight: 500;
  background-color: #f8f9fb;
}
ul {
  float: right;
  padding-right: 1%;
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
  color: #278ed2;
}
</style>
