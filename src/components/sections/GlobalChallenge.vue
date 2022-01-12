<template>
  <div class="global-challenge">
      <h2 class="secondary-color">GLOBAL CHALLENGE. WORLD CLASS RESPONSE</h2>
      <div class="linea"></div>
      <div class="container">
          <div class="column">
              <h3>our people</h3>
              <Cards v-for="(people, index) in peoples" :key="index" :image="people.src" :nome="people.nome"/>
          </div>
          <div class="column">
              <h3>our practice areas</h3>
          </div>
          <div class="column">
              <h3>our publications</h3>
          </div> 
      </div>
  </div>
</template>

<script>
import Cards from '../elements/Cards.vue';
export default {
    name: 'GlobalChallenge',
    components: {
        Cards
    },
    data(){
        return{
            peoples: [
                {
                    src: "../../assets/images/column1-image1.jpg",
                    alt: "column1-image1.jpg",
                    nome: "Deborah Brown"
                },
                {
                    src: "../../assets/images/column1-image2.jpg",
                    alt: "column1-image2.jpg",
                    nome: "Allen Lucas"
                },
                {
                    src: "../../assets/images/column1-image3.jpg",
                    alt: "column1-image3.jpg",
                    nome: "Muriel Potter"
                },
                {
                    src: "../../assets/images/column1-image4.jpg",
                    alt: "column1-image4.jpg",
                    nome: "Ken Douglas"
                },
                {
                    src: "../../assets/images/column1-image5.jpg",
                    alt: "column1-image5.jpg",
                    nome: "Loretta Harris"
                },
                {
                    src: "../../assets/images/column1-image6.jpg",
                    alt: "column1-image6.jpg",
                    nome: "Phil Russell"
                },
            ]
        }
        
    }
}
</script>

<style lang="scss" scoped>
    .global-challenge{
        
        padding-top: 130px;
        margin-top: 0px;
        padding-right: 30px;
        padding-bottom: 130px;
        margin-bottom: 0px;
        padding-left: 30px;

        h2{
            text-align: center;
        }
        .linea{
            border-bottom: 1px solid #dfdddd;
            width: 170px;
            margin: auto;
            margin-top: 30px;
        }
        .column{
            width: calc(100% / 3);
        }
        h3{
            text-align: start;
        }
    }
</style>