<template>
  <div>
    <h1 class="title">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "Heading",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.title {
  margin-bottom: 50px;
  font-family: 'Sacramento', cursive;
  font-size: 4.5625rem;
  font-weight: bold;
  text-shadow: 5px 5px 5px silver;
}
</style>
