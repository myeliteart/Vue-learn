<template>
  <div>
    <div class="container py-4 px-3 mx-auto">
      <h1>Hello, Bootstrap and Vite!</h1>
      <button class="btn btn-primary">Primary button</button>
    </div>
   <navBar></navBar>
  </div>
</template>

<script>
import navBar from './components/navBar.vue';
  export default {
    data () {
      return {
        
      }
    },
    components: {
      navBar
    }
  }
</script>

<style>

</style>