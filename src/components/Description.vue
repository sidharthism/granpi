<template>
  <div class="desc">
    <ul>
      <li>
        <a href="about.html" @click="viewAbout" rel="noopener">About</a>
      </li>
      <li>
        <a href="https://github.com/keithwhor/audiosynth" target="_blank" rel="noopener">audioSynth.js</a>
      </li>
    </ul>
    <h3>Made with <span style="color: red;"><i class="fa fa-heart" aria-hidden="true"></i></span> by <a href="https://github.com/sidharthism" target="_blank" rel="noopener">@sidharthism</a></h3>
  </div>
</template>

<script>
export default {
  name: "Description",
  methods: {
    viewAbout: function(){

    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0;
  font-family: 'Open Sans', cursive;
  font-weight: 500;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #2c3e50;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
.desc {
  margin: 70px auto 0;
}
</style>
