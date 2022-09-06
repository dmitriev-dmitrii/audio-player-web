
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
import appPlayer from './components/appPlayer.vue';
export default {
  components :{ appPlayer },
  data:()=> { return {

  }
  },

}
</script>

