<template>
  <div class="box">
      <img :src="image" alt="">
       <span class="secondary-font"><strong>{{nome}}</strong></span>
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

<style>

</style>