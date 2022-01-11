<template>
  <header>
      <div class="header-sup">
          <div class="container">
              <div id="announce">
                <span>Avada & Associates legal team announce deal to open up oil & gas</span>
              </div>
              <div class="socials-container">
                  <Socials/>
              </div>
          </div>
          
      </div>
  </header>
</template>

<script>
import Socials from '../elements/Socials.vue';

export default {
    name: 'Header',
    components: {
        Socials
    }
}
</script>

<style lang="scss" scoped>
    .container{
        display: flex;
    }
    
    i{
        font-size: 30pt;
    }
</style>