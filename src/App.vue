<template>
  <img alt="penny logo" height="500" src="https://lh3.googleusercontent.com/pw/AMWts8BX-tGjTK4-vlhbskroDO0wVPi-o9NbmcdOvdBvqOoQaz_OZR8TQ4JmLMNUSx59pjWlxk3GUqvDNm4tAMtHONqaPxfd-beVN4NPv1Y-5wqb8eIlUHDhQBu-LfdSvs4Ms9EIrZ7H14IcLiWwIiXl0vOu7Q=w486-h648-s-no">
  <HelloWorld msg="Penny 的澳洲生活"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
