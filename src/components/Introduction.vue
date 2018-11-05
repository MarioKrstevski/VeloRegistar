<template>
  <div class="background">
    <div class="main-content">
        <h1>Регистрирај се. Пријави. Заштити! 
        </h1>
        <p> Придружете ни се да ги намалиме<br>
            кражбите низ Македонија
        </p>
        <br>
        <br>
        <span>Сакам велосипедот да го:</span>
        <br>
         <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLScMV3CrnkpFKblibiX874Qd_GEZK84t7UqBmY-SjY6zq9Zm5w/viewform"> <button class="register">
        
        Регистрирам</button></a>
         <a target="_blank" href="https://docs.google.com/forms/d/e/1FAIpQLSclzPLH4bQdIlcrh3rmpi2i0zv_oO8gY62-5zO-ETAHqQCeKg/viewform">
         <button class="stolen"> 
       
        Пријавам за украден </button></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Introduction"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.background {
  width: 100%;
  height: 480px;
  background-color: #f8f9fb;
  font-family: "Open Sans", Tahoma, "Helvetica Neue", Helvetica, Arial,
    sans-serif;
  font-weight: 200;
  text-align: center;
  color: rgb(95, 95, 95);
}
h1 {
  font-weight: 300;
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
  padding: 0px 12px;
  margin: 15px 10px;
  height: 50px;
  min-width: 150px;
  border-radius: 7px;
  outline: none;
  border: none;
  cursor: pointer;
}
.register {
  transition: background-color 250ms ease-in;
  background-color: #278dd2;
  color: white;
}
.register:hover {
  transition: background-color 250ms ease-in;
  background-color: #fff;
  border: 1.2px solid #77b8e4;
  color: #278dd2;
}
.stolen {
  background-color: rgb(244, 251, 253);
  border: 1.2px solid #278dd2;
  transition: border 250ms ease-out;
  color: #278dd2;
}
.stolen:hover {
  transition: border 250ms ease-out;
  border: 1.2px solid #cce7f8;
  background-color: #fff;
}
</style>
