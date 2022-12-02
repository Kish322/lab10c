<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">The count is {{ count }}</button>
    
  </div>
  <h1> The Installation of the Framework </h1>
    <p>  For this assignment, I decided to go with a framework called vue.js + vite. 
    The installation was tedious for me to do, as I had to follow each and every step of the process
    to create the components. The difficulties that I have encountered was trying to figure out 
    how to exactly deploy the web page. I decided that the best option was to host it on Github Pages where I could use CI/CD Integration to 
    successfully confirm the webpage deployment. 
  
  </p>
  <p>

    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      ></a
    >
  </p>
  <p>

    <a href="https://github.com/johnsoncodehk/volar" target="_blank"></a>
   
  </p>
  <p class="read-the-docs"></p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>

