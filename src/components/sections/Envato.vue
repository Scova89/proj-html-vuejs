<template>
    <div class="sezione-envato">
       <div class="container-envato">
            <div class="logo">
                <img src="../../assets/images/envato-logo.png" alt="envato logo">
            </div>
      
            <p>“We have worked with Avada Law for the past 15 years. As we have grown and evolved, what I have valued most about our relationship is that Avada Law knows us and our business.”</p>
            <h2>Nigel Rawlinson • Senior Partner</h2>
        </div>

        <div class="identità-azienda bg-terziary-color">
            <div class="container bg-terziary-color-bordertop">
                <div class="box">
                    <div class="foto">
                        <img src="../../assets/images/law_7.jpg" alt="law 7">
                    </div>
                    <h3>international</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                </div>

                <div class="box">
                    <div class="foto">
                        <img src="../../assets/images/law_8.jpg" alt="law 8">
                    </div>
                    <h3>partnership</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    
                </div>

                <div class="box">
                     <div class="foto">
                        <img src="../../assets/images/law_3.jpg" alt="law 3">
                    </div>
                    <h3>excellence</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    
                </div>

        </div>


      </div>
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
        
          .foto{
            display: flex;
            justify-content: center;
            margin-bottom: 30px;
          }
          
        } 
      
      }
    }

</style>