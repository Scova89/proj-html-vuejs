<template>
  <main>
      <Jumbotron/>

      <!-- sezione riguardante l'identità dell'azienda-->
      <div class="identità-azienda bg-terziary-color">
        <div class="container bg-terziary-color-bordertop">
          <div class="box">
            <h3>who we are</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis praesentium aut sunt quibusdam placeat, iure sapiente in obcaecati nihil omnis distinctio incidunt, nisi repellendus consectetur sit. Sed, sapiente.</p>
            <div class="pulsante">
              <Buttons/>
            </div>
            
          </div>
          <div class="box"></div>
          <div class="box"></div>
        </div>


      </div>
  </main>
</template>

<script>
import Jumbotron from '../sections/Jumbotron.vue';
import Buttons from '../elements/Buttons.vue';

export default {
    name: 'Main',
    components: {
      Jumbotron,
      Buttons
    }
}
</script>

<style lang="scss" scoped>
  .identità-azienda{
    display: flex;
    justify-content: center;
    padding: 110px 30px 90px;

    .container{
      justify-content: space-between;

      .box{
      background-color: white;
      width: calc(100% / 3 - 2px);
      padding: 40px 50px 48px;
      
        .pulsante{
          display: flex;
          justify-content: center;

          
        }
        
      } 
    
    }
  }
  
</style>