<template>
  <div id="app" >
    <Header />
    <Introduction/>
    <About/>
    <MemberList/>
    <Contact/>
  </div>
</template>

<script>
import Header from "./components/Header";
import Introduction from "./components/Introduction";
import About from "./components/About";
import MemberList from "./components/MemberList";
import Contact from "./components/Contact";

export default {
  name: "App",
  components: {
    Introduction,
    Header,
    About,
    MemberList,
    Contact
  }
};
</script>

<style>
</style>
