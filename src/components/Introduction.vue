<template>
  <div class="background">
    <div class="main-content">
         <h1>Protect your bike <br>
against theft and damage in minutes.</h1>

    <h3>Register your bike in a free, international database. <br>
For full protection, insure!
 </h3>

 <br>
 <br>
 
 <span>I want to</span>
 <br>

 <button class="register"> <a href="https://docs.google.com/forms/d/e/1FAIpQLScMV3CrnkpFKblibiX874Qd_GEZK84t7UqBmY-SjY6zq9Zm5w/viewform">Register my bike</a></button>
 <button class="stolen"> <a href="https://docs.google.com/forms/d/e/1FAIpQLSclzPLH4bQdIlcrh3rmpi2i0zv_oO8gY62-5zO-ETAHqQCeKg/viewform">Report stolen bike</a> </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Introduction",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.background {
  width: 100%;
  height: 600px;
  background-color: #f8f9fb;
  font-family: "Open Sans", Tahoma, "Helvetica Neue", Helvetica, Arial,
    sans-serif;
  font-weight: 200;
  text-align: center;
  color: rgb(77, 75, 75);
}
a,
a:visited,
a:hover,
a:active {
  color: black;
  text-decoration: none;
}
.main-content {
  padding-top: 100px;
  /* transform: translate(50%, -50%); */
}
button {
  font-size: 15px;
  margin: 15px 10px;
  height: 50px;
  width: 150px;
  border-radius: 7px;
  outline: none;
  border: none;
  cursor: pointer;
}
.register {
  transition: background-color 250ms ease-in;
  background-color: #278dd2;
}
.register a {
  color: white;
}
.register:hover {
  transition: background-color 250ms ease-in;
  background-color: #fff;
  border: 1.2px solid #77b8e4;
}

.register:hover a {
  color: #278dd2;
}

.stolen {
  background-color: rgb(244, 251, 253);
  border: 1.2px solid #278dd2;
  transition: border 250ms ease-out;
}
.stolen a {
  color: #278dd2;
}
.stolen:hover {
  transition: border 250ms ease-out;
  border: 1.2px solid #fff;
  background-color: #fff;
}
</style>
