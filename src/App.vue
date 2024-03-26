<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Navigation from './components/Navigation.vue'
import Status_bar from './components/status_bar.vue'
</script>

<template>
  <div class="wrapper">
    <header>
      <div class="container">
        <Navigation />
      </div>
    </header>
    <main>
      <div class="container">
        <Status_bar />
      </div>
      <div class="container">
        <div class="col">col1</div>
        <div class="col">col2</div>
      </div>
    </main>
    <footer></footer>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style lang="scss"></style>
