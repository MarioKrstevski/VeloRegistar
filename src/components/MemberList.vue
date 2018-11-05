<template>
    <div id="our-team">
        <div class="row">
           <Member name="Марјан" occupation="Server Master"/>
           <Member  name="Ивона" occupation="CEO"/>
           <Member  name="Александар" occupation="Clean Designer"/>
        </div>
        <div class="row">
            <Member  name="Ели" occupation="Marketing Guru"/>
            <Member name="Марио" occupation="Front-End Developer"/>
        </div>
    </div>
</template>

<script>
import Member from "../components/Member.vue";

export default {
  name: "MemberList",
  components: {
    Member
  }
};
</script>

<style scoped>
#our-team {
  padding-top: 10px;
  background: #f8f9fb;
  height: 560px;
}
.row {
  display: flex;
  justify-content: center;
  margin: 12px;
  align-content: center;
  height: 260px;
}
</style>
