<template>
  <div class="identità-azienda bg-terziary-color">
        <div class="container bg-terziary-color-bordertop">
          <div class="box">
            <h3>who we are</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis praesentium aut sunt quibusdam placeat, iure sapiente in obcaecati nihil omnis distinctio incidunt.</p>
            <div class="pulsante">
              <button class="bg-secondary-color primary-font">learn more</button>
            </div>
          </div>

          <div class="box">
            <h3>what we do</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis praesentium aut sunt quibusdam placeat, iure sapiente in obcaecati nihil omnis distinctio incidunt.</p>
            <div class="pulsante">
              <button class="bg-secondary-color primary-font">learn more</button>
            </div>
          </div>

          <div class="box">
            <h3>where we work</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis praesentium aut sunt quibusdam placeat, iure sapiente in obcaecati nihil omnis distinctio incidunt.</p>
            <div class="pulsante">
              <button class="bg-secondary-color primary-font">learn more</button>
            </div>
          </div>

        </div>


      </div>
</template>

<script>
export default {
    name: 'Identita'
}
</script>

<style lang="scss" scoped>
    .identità-azienda{
      width: 100%;
      display: flex;
      justify-content: center;
      padding: 110px 30px 90px;

      .container{
        justify-content: space-between;
        max-width: 1080px;

        .box{
        background-color: white;
        width: calc(100% / 3 - 2px);
        padding: 40px 50px 48px;
        
          .pulsante{
            display: flex;
            justify-content: center;

            button{
            text-transform: uppercase;
            color: white;
            padding: 13px 29px;
            border-radius: 2px;
            font-size: 14px;
            font-weight: bold;
            cursor: pointer;
            border: none;
              
            }

            button:hover{
                background-color: #55a098;
            }
          }
          
        } 
      
      }
  }
</style>