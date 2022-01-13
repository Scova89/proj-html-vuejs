<template>
  <div class="container-envato">
      <div class="logo">
          <img src="../../assets/images/envato-logo.png" alt="envato logo">
      </div>
      
      <p>“We have worked with Avada Law for the past 15 years. As we have grown and evolved, what I have valued most about our relationship is that Avada Law knows us and our business.”</p>
      <h2>Nigel Rawlinson • Senior Partner</h2>
  </div>
</template>

<script>
export default {
    name: 'Envato'
}
</script>

<style lang="scss" scoped>
    .container-envato{
        background-image: url(../../assets/images/showeare-parallax.jpg);
        padding: 80px 60px;
        margin-bottom: 0px;
        background-repeat: no-repeat;
        background-size: cover;
        background-position-y: -260px;
        

        .logo{
            display: flex;
            justify-content: center;

            img{
            width: 150px;
            }
        }
        

        p{
            color: white;
            font-style: italic;
            line-height: 30px;
            font-size: 18px;
            text-align: center;
            letter-spacing: 2px;
        }

        h2{
            color: white;
            text-align: center;
            letter-spacing: 2px;
        }
    }
    

</style>