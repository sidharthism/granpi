<template>
  <div id="app">
    <Heading msg="GranPi"/>
    <KeyBoard id="keyBoard"/>
    <Description/>
  </div>
</template>

<script>
import Heading from "./components/Heading";
import KeyBoard from "./components/KeyBoard";
import Description from "./components/Description";

export default {
  name: "App",
  components: {
    Heading,
    KeyBoard,
    Description
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Sacramento&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans&display=swap');
body {
  margin: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-width: 76rem;
  background-color: #f1f1f1;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
</style>
