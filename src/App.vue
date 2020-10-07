<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div class="main">
    <h1>cheryl-ng</h1>
    <!-- <p>about me</p>
    <p>projects</p>
    <p>resume</p> -->
    <ul>
      <li><a href="https://www.linkedin.com/in/cherylnqj/" target="_blank" rel="noopener">about me</a></li>
      <li><a href="https://github.com/Yoshi275" target="_blank" rel="noopener">projects</a></li>
      <li><a href="https://drive.google.com/file/d/1B8iHDLdAKMd7LMT4Fzz-JB-kUTVB-c7n/view?usp=sharing" target="_blank">resume</a></li>
      <li><a href="https://drive.google.com/file/d/1xYYv1UOrZh7Hj2PGP7G4OZdXWnbnHSQ-/view?usp=sharing" target="_blank">portfolio</a></li>
    </ul>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');

#app {
  font-family: 'Roboto Mono', Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  /* display: inline-block; */
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
