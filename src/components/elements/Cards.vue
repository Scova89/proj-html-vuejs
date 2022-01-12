<template>
  <div class="box bg-terziary-color">
    <img :src="image" :alt="nome">
    <span class="secondary-font">{{nome}}</span>
  </div>
</template>

<script>
export default {
    name: 'Cards',
    props:{
        image: String,
        nome: String
    }
}
</script>

<style lang="scss" scoped>

    .box{
        display: flex;
        padding: 25px;
        align-items: center;
        
        margin-top: 20px;
        margin-bottom: 10px;

        img{
            width: 20%;
            margin-right: 20px;
        }

        span{
            font-weight: bold;
            font-size: 14px;
        }
    }
    
    
    

</style>