
<template>
  <div>
    <h1> h1
    </h1>
    <app-player />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
<script>
import AppPlayer from './components/AppPlayer.vue';

export default {
  components :{ AppPlayer },
  data:()=> { return {

  }
  },

}
</script>

