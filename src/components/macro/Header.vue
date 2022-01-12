<template>
  <header>
      <div class="header-sup">
          <div class="container">
              <div id="announce">
                <span class="secondary-font">Avada & Associates legal team announce deal to open up oil & gas</span>
              </div>
              <div class="socials-container">
                  <Socials/>
              </div>
          </div>
          
      </div>
      <div class="header-inf">
          <div class="container">
              <img src="../../assets/images/avada-law-logo.png" alt="">
              <nav>
                  <NavBar v-for="(link, index) in links" :key="index" :link="link"/>
              
              </nav>
          </div>
          
      </div>
  </header>
</template>

<script>
import Socials from '../elements/Socials.vue';
import NavBar from '../sections/NavBar.vue';

export default {
    name: 'Header',
    components: {
        Socials,
        NavBar
    },
    data(){
        return {
            links:[
                {
                    text: "Home",
                    url: "#",
                    state: true
                },
                {
                    text: "Who We Are",
                    url: "#",
                    state: false
                },
                {
                    text: "What We Do",
                    url: "#",
                    state: false
                },
                {
                    text: "Where We Work",
                    url: "#",
                    state: false
                },
                {
                    text: "Careers",
                    url: "#",
                    state: false
                },
                {
                    text: "News",
                    url: "#",
                    state: false
                },
                {
                    text: "Contact",
                    url: "#",
                    state: false
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
    
    .header-sup {
        display: flex;
        justify-content: center;
        background-color: #f5f5f5;
        border-top: 3px solid #55a098;

        .container{
        justify-content: space-between;
        align-items: center;
        }
    }

    span{
        font-size: 12px;
        color: #666666;
    }
    .header-inf{
        display: flex;
        justify-content: center;
        min-height: 102px;
        .container{
            align-items: center;
            justify-content: space-between;
        }
        
    }
    nav{
        display: flex;
        
    }
    
</style>