<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="#" target="_blank">
      <img src="/pngegg-2.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="#" target="_blank">
      <img src="/pngegg-3.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="#" target="_blank">
      <img src="/pngegg.svg" class="logo" alt="Vite logo" />
    </a>
    
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Which House you Truely Belong to" />
  <audio
        controls 
        src="/Still.mp3">
            
            <code>audio</code> element.
    </audio>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
