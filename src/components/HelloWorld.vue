<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      我的早餐
      <a href="https://photos.google.com/share/AF1QipPIEgEPnIlNyvPXEcecKN8jmW6LVA1owBTEx5oEXLR1uQ4ekDfOeATi0-8oiQdtXw?key=eEtCYnRsWUlvemRBOXhKdWRPSVVNcHZ3c0wtYlJ3" target="_blank" rel="noopener">相簿</a>.
    </p>
    <h3>風景</h3>
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
