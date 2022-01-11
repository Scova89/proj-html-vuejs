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
    .header-sup{
        display: flex;
        justify-content: center;
        background-color: #f5f5f5;
        border-top: 3px solid #55a098;
    }
    .header-sup .container{
        justify-content: space-between;
        align-items: center;
    }
    span{
        font-size: 12px;
        color: #666666;
    }
    
    
</style>