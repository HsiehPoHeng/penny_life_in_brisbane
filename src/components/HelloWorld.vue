<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      我的早餐
      <a href="https://photos.google.com/share/AF1QipPIEgEPnIlNyvPXEcecKN8jmW6LVA1owBTEx5oEXLR1uQ4ekDfOeATi0-8oiQdtXw?key=eEtCYnRsWUlvemRBOXhKdWRPSVVNcHZ3c0wtYlJ3" target="_blank" rel="noopener">點我->>>相簿</a>.
    </p>
    <h3>各種風景</h3>    
    <video width="320" height="240" controls>
  <source src="../assets/video/1680409743015.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
    <br>
    <a href="https://photos.google.com/album/AF1QipMHdeCrVsYTBYPMUcEj5XsIH0HMptVHWkdy1ZeE" target="_blank" rel="noopener">點我->>>風景</a>.
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #42b983;
}
</style>
