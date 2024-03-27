<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Navigation from './components/Navigation.vue'
import Status_bar from './components/status_bar.vue'
import Products from './components/Products.vue'
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
        <div class="col">
          <Products />
        </div>
        <div class="col">
          <h1 class="col-header">Diet</h1>
        </div>
      </div>
    </main>
    <footer></footer>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style lang="scss"></style>
