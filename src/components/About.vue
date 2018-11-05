<template>
    <div id="mission">
        <div class="the-idea">
            <h2>Регистрирај го велосипедот БЕСПЛАТНО кај нас</h2>
            <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit minima, excepturi rerum cupiditate quo voluptas accusantium nisi eligendi pariatur molestiae porro iure amet fugiat distinctio officiis. Voluptatibus eligendi ducimus ipsa, minima officiis alias vitae, perferendis eos enim quos esse perspiciatis, laudantium veniam ad aperiam. </p>
        </div>
        <div class="image">
            <img src="../assets/asphalt-bicycle-bike-686230.jpg" alt="Nenajdena slika">
        </div>
    </div>
</template>

<script>
export default {
  name: "About"
};
</script>

<style scoped>
#about {
  height: 460px;
  margin-top: -21px;
  color: rgb(70, 70, 70);
  background-color: #f8f9fb;
}
.the-idea {
  background-color: #f8f9fb;
  float: left;
  width: 49%;
  display: inline-block;
  padding: 100px 30px 30px 30px;
  box-sizing: border-box;
  height: 445px;
}
.the-idea h2 {
  text-align: center;
}
.image {
  background-color: #f8f9fb;
  float: right;
  top: 0;
  width: 50.9%;
  height: 445px;
  box-sizing: border-box;
  display: inline-block;
}
.image img {
  width: 100%;
  height: 100%;
}
#mission:after {
  content: "";
  display: table;
  clear: both;
}
</style>
