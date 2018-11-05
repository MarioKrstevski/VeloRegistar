<template>
    <div class="member">
       <img src="../assets/logo.png" alt="Logo">

       <h2>

       {{name}}
       </h2>
       <p>

       {{occupation}}
       </p>
    </div>
</template>

<script>
export default {
  name: "Member",
  props: ["name", "occupation"]
};
</script>

<style scoped>
.member {
  border-radius: 13%;
  text-align: center;
  margin: 9px;
  display: inline-block;
  height: 100%;
  width: 33%;
  max-width: 300px;
  background-color: #278ed2a9;
  transition: all 0.2s ease-in;
}
.member:hover {
  transform: scale(1.07);
  background-color: #278ed2;
  box-shadow: 0 5px 15px -5px #1f71a8;
  transition: all 0.4s ease-out;
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
  background-color: #fff;
  margin-top: 12px;
  border-radius: 50%;
  height: 70%;
  width: 70%;
}
</style>
