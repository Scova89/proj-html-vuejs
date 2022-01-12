<template>
  <main>
      <Jumbotron/>

      <!-- sezione riguardante l'identità dell'azienda-->
      <Identita/>

      <!-- sezione delle skills dell'azienda -->
      <Skills/>

      
  </main>
</template>

<script>
import Jumbotron from '../sections/Jumbotron.vue';
import Identita from '../sections/Identita.vue';
import Skills from '../sections/Skills.vue';


export default {
    name: 'Main',
    components: {
      Jumbotron,
      Identita,
      Skills
    }
}
</script>

<style lang="scss">
  
  
</style>