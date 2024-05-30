<script setup lang="ts">
import TheWelcome from './components/TheWelcome.vue'
import Nav from './components/Nav.vue'
import {Button} from './components/ui/button'
import {Input} from './components/ui/input'
</script>

<template>
  <div>
    <Nav msg="Vue.js Test"></Nav>
  </div>
  

  <div class="flex py-4 px-2">
    <Button>Submit</Button>
    <Input class="mx-2"></Input>
 </div>
</template>

<style scoped>
header {

}

.logo {
  display: block;

}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
