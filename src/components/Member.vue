<template>
    <div class="member">
       <div class="overlay"></div>    
       <div class="names" :style="font">
            {{name}}</div>  
       <img :src="url" alt="Member Image"> 
    </div>
</template>

<script>
export default {
  name: "Member",
  props: ["name", "url", "font"]
};
</script>

<style scoped>
.member {
  text-align: center;
  display: inline;
  height: 100%;
  width: 19.9%;
  transition: all 0.2s ease-in;
}
.member:hover {
  /* transform: scale(1.07);
  background-color: #278ed2;
  box-shadow: 0 5px 15px -5px #1f71a8;
  transition: all 0.4s ease-out; */
}

.names {
  visibility: hidden;
  z-index: 20;
  color: white;
  width: 19.9%;
  height: 25vw;
  line-height: 25vw;
  font-size: 3vw;
  position: absolute;
}
.member:hover > .names {
  visibility: visible;
}

.member:hover > .overlay {
  z-index: 10;
  width: 19.9%;
  height: 25vw;
  position: absolute;
  background-color: #000;
  opacity: 0.7;
}
p,
h2 {
  margin: 0;
  padding: 0;
}
p {
  color: rgb(29, 29, 29);
}
img {
  height: 100%;
  width: 100%;
}
</style>
