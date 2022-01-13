<template>
  <main>
      <Jumbotron/>

      <!-- sezione riguardante l'identità dell'azienda-->
      <Identita/>

      <!-- sezione delle skills dell'azienda -->
      <Skills/>

      <!-- domande agli esperti -->
      <Experts/>

      <!-- sezione delle schede del team, dell'area di lavoro e delle pubblicazioni -->
      <GlobalChallenge/>

      <!-- sezione con logo Envato -->
      <Envato/>

      
  </main>
</template>

<script>
import Jumbotron from '../sections/Jumbotron.vue';
import Identita from '../sections/Identita.vue';
import Skills from '../sections/Skills.vue';
import Experts from '../sections/Experts.vue';
import GlobalChallenge from '../sections/GlobalChallenge.vue';
import Envato from '../sections/Envato.vue';

export default {
    name: 'Main',
    components: {
      Jumbotron,
      Identita,
      Skills,
      Experts,
      GlobalChallenge,
      Envato
    },
    
}
</script>

<style lang="scss">
  
  
</style>