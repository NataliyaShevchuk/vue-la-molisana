<script>
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';

export default{
  components: { TheHeader, TheFooter },

  data() {
    return {
      
    }
  },
}
</script>

<template>

<TheHeader></TheHeader>

<main>
    <div class="container">
      <h1 class="my-text-primary"> La MOLISANA </h1> 
    </div>
</main>

<TheFooter></TheFooter>
</template>

<style lang="scss">
@use "./styles/partials/variables" as *;

footer{
  border-top: 1px solid $border-color;
}

</style>
