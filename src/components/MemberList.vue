<template>
    <div id="our-team">
        <span id="the-team">The Team </span>
        <div class="row">
            <Member name="MARJAN" :url="marjanImageUrl" :font="marjanFontStyle"/>
            <Member  name="IVONA" :url="ivonaImageUrl" :font="ivonaFontStyle"/>
            <Member  name="ALEKSANDAR" :url="aleksandarImageUrl" :font="aleksandarFontStyle"/>
            <Member  name="ELI" :url="eliImageUrl" :font="eliFontStyle"/>
            <Member name="MARIO" :url="marioImageUrl" :font="marioFontStyle"/>
        </div>
    </div>
</template>

<script>
import Member from "../components/Member.vue";

export default {
  name: "MemberList",
  components: {
    Member
  },
  data() {
    return {
      marioImageUrl: require("../assets/mario-resized.png"),
      marioFontStyle: "font-family:Times, serif",
      ivonaImageUrl: require("../assets/ivona-resized.png"),
      ivonaFontStyle: "font-family:Courier New, monospaced",
      marjanImageUrl: require("../assets/marjan-resized.png"),
      marjanFontStyle: "font-family:Palatino, serif",
      eliImageUrl: require("../assets/eli-resized.png"),
      eliFontStyle: "font-family:Comic Sans, sans-serif",
      aleksandarImageUrl: require("../assets/aleksandar-resized.png"),
      aleksandarFontStyle: "font-family:Impact, sans-serif"
    };
  }
};
</script>

<style scoped>
#our-team {
  text-align: center;
  color: #278dd2;
  background-color: #f8f9fb;
  padding-top: 30px;
}
#the-team {
  color: #278dd2;
  font-family: "Lato", sans-serif;
  font-style: normal;
  font-weight: 700;
  text-transform: uppercase;
  font-size: 45px;
  position: relative;
  margin: 10;
  padding: 10px 0;
}
#the-team::after,
#the-team::before {
  content: "";
  position: absolute;
  top: 50%;
  height: 5px;
  width: 9999px;
  display: block;
  margin-top: -1px;
  background-color: #278dd2;
}

#the-team::after {
  left: 100%;
  margin-left: 0.5em;
}

#the-team::before {
  right: 100%;
  margin-right: 0.5em;
}

.row {
  padding-top: 30px;
  display: flex;
  justify-content: center;
  align-content: center;
  height: 25vw;
}
</style>
