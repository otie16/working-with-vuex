<template>
  <div id="app">
     <Component1 />
  </div>
</template>

<script>
import Component1 from './components/Component1.vue'

export default {
    name: 'app',
    components: {
       Component1
    },
    data () {
        return {
           
        }
    }
}
</script>

<style>
body{
    font-family: Ubuntu;
    color: #555;
    text-align: center;
}
</style>
