<template>
  <div>
    
    <ClickCounter />
    <HoverCounter />

  </div>
 
</template>

<script>
import ClickCounter from './components/ClickCounter.vue';
import HoverCounter from './components/HoverCounter.vue';

export default {
  name: 'App',
  components: {
    ClickCounter, HoverCounter
  },
  data() {
    return {
      
    }
  },
  provide() {
    return { 
      
    }
  },
  methods: {},
  computed: {},
  watch: {},
  
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

html,
body,
#app {
  margin: 0;
  padding: 0;
  height: 100%;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.container {
  height: 100%;
  display: grid;
  justify-content: center;
  align-items: center;
}

.content {
  max-width: 400px;
  position: relative;
}

</style>
