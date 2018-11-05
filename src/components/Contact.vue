<template>
    <div id="contact">
       <h3> Контактирајте не на Facebook </h3>
       <div class="social-media">
           <div class="overflow-hidden">

                <a class="button-behaviour" target="_blank" href="https://www.facebook.com/veloregistar/">
                    <i class="fab fa-facebook-f"></i>
                </a>
           </div>
       </div>
       <br>
       <br>
       <p>Copyright 2018 - All Rights Reserved</p>
    </div>
</template>

<script>
export default {
  name: "Contact"
};
</script>

<style>
#contact {
  margin-top: -21px;
  padding-top: 65px;
  height: 250px;
  width: 100%;
  background-color: #f8f9fb;
  text-align: center;
}
.button-behaviour {
  display: inline-block;
  width: 90px;
  height: 90px;
  background: #cfdaf1;
  line-height: 90px;
  border-radius: 30%;
  box-shadow: 0 5px 15px -5px #000070;
}
.button-behaviour:active {
  box-shadow: 0 7px 15px -5px #000070;
}
.button-behaviour i {
  color: #278dd2;
  font-size: 26px;
  transition: 0.2s linear;
}

.button-behaviour:hover i {
  transform: scale(1.3);
}
</style>

