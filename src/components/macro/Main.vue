<template>
  <main>
      <Jumbotron/>

      <!-- sezione riguardante l'identità dell'azienda-->
      <Identita/>
      
  </main>
</template>

<script>
import Jumbotron from '../sections/Jumbotron.vue';
import Identita from '../sections/Identita.vue';

export default {
    name: 'Main',
    components: {
      Jumbotron,
      Identita
    }
}
</script>

<style lang="scss">
  
  
</style>