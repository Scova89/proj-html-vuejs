<template>
  <div class="global-challenge">
      <h2 class="secondary-color">GLOBAL CHALLENGE. WORLD CLASS RESPONSE</h2>
      <div class="linea"></div>
      <div class="container">
          <div class="column">
              <h3>our people</h3>
              <Cards v-for="(people, index) in peoples" :key="index" :image="people.img" :nome="people.nome"/>
          </div>
          <div class="column">
              <h3>our practice areas</h3>
              <Cards v-for="(area, index) in areas" :key="index" :image="area.img" :nome="area.nome"/>
          </div>
          <div class="column">
              <h3>our publications</h3>
              <Cards v-for="(publication, index) in publications" :key="index" :image="publication.img" :nome="publication.nome"/>

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
                    img: require ("../../assets/images/column1-image1.jpg"),
                    nome: "Deborah Brown"
                },
                {
                    img: require ("../../assets/images/column1-image2.jpg"),
                    nome: "Allen Lucas"
                },
                {
                    img: require ("../../assets/images/column1-image3.jpg"),
                    nome: "Muriel Potter"
                },
                {
                    img: require ("../../assets/images/column1-image4.jpg"),
                    nome: "Ken Douglas"
                },
                {
                    img: require ("../../assets/images/column1-image5.jpg"),
                    nome: "Loretta Harris"
                },
                {
                    img: require ("../../assets/images/column1-image6.jpg"),
                    nome: "Phil Russell"
                },
            ],

            areas: [
                {
                    img: require ("../../assets/images/column2-image1.jpg"),
                    nome: "Tax Litigation"
                },
                {
                    img: require ("../../assets/images/column2-image2.jpg"),
                    nome: "Aquisitions"
                },
                {
                    img: require ("../../assets/images/column2-image3.jpg"),
                    nome: "Financial Advice"
                },
                {
                    img: require ("../../assets/images/column2-image4.jpg"),
                    nome: "International"
                },
                {
                    img: require ("../../assets/images/column2-image5.jpg"),
                    nome: "Oil and Gas"
                },
                {
                    img: require ("../../assets/images/column2-image6.jpg"),
                    nome: "Capital Markets"
                },
            ],

            publications: [
                {
                    img: require ("../../assets/images/column3-image1.jpg"),
                    nome: "Low Oil Prices"
                },
                {
                    img: require ("../../assets/images/column3-image2.jpg"),
                    nome: "Cost of Divorce"
                },
                {
                    img: require ("../../assets/images/column3-image3.jpg"),
                    nome: "2015 Tax Laws"
                },
                {
                    img: require ("../../assets/images/column3-image4.jpg"),
                    nome: "Surveys Matter"
                },
                {
                    img: require ("../../assets/images/column3-image5.jpg"),
                    nome: "In-House Work"
                },
                {
                    img: require ("../../assets/images/column3-image6.jpg"),
                    nome: "Obama Care"
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
            margin-bottom: 40px;
        }
        .column{
            width: calc(100% / 3);
            padding: 0 30px;
        }
        h3{
            text-align: start;
            margin-bottom: 20px;
        }
    }
</style>