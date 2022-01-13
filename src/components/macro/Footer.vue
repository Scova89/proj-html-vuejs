<template>
  <footer>
      <!-- sezione Work Together -->
      <WorkTogether/>

      <!-- navbar del footer -->
      <div class="footer-inf">
          <div class="container"><h3 class="secondary-font">CALL OUR EXPERTS TODAY 1.800.555.6789</h3></div>
          
          <div class="container">
              
              <nav>
                  <NavBarFooter v-for="(link, index) in links" :key="index" :link="link"/>
              
              </nav>

              <div class="socials-container">
                  <Socials/>
              </div>
          </div>
          
      </div>


  </footer>
</template>

<script>
import WorkTogether from '../sections/WorkTogether.vue';
import NavBarFooter from '../sections/NavBarFooter.vue';
import Socials from '../elements/Socials.vue';
export default {
    name: 'Footer',
    components: {
      WorkTogether,
      NavBarFooter,
      Socials
    },
    data(){
        return {
            links:[
                {
                    text: "© Copyright 2015 |",
                    url: "#",
                    state: false
                },
                {
                    text: "Avada Theme by ThemeFusion |",
                    url: "#",
                    state: false
                },
                {
                    text: "All Rights Reserved |",
                    url: "#",
                    state: false
                },
                {
                    text: "Powered by WordPress",
                    url: "#",
                    state: false
                },
                
            ]
        }
    }
}
</script>

<style lang="scss">
  .footer-inf{
      padding-top: 24px;
      margin-top: 0px;
      padding-right: 30px;
      padding-bottom: 24px;
      margin-bottom: 0px;
      padding-left: 30px;
      min-height: 102px;

      .container{
          max-width: 1080px;
          align-items: center;
          justify-content: space-between;

          h3{
            margin: 14px 0;
          }

        
          nav{
          display: flex;
          }
      }

          
  }

</style>