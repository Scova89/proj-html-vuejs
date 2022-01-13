<template>
  <div class="container-img" primary-font>
    <h2 class="primary-font">let's work together</h2>
    <div class="linea"></div>
    <p class="primary-font">We work as a single united team with market leading firms around the world and give our clients the highest quality advice possible.</p>
    <div class="pulsante">
        <button class="primary-font">make enquiry</button>
    </div>
    
  </div>
</template>

<script>
export default {
    name: 'WorkTogether'
}
</script>

<style lang="scss" scoped>
    .container-img{
            background-image: url(../../assets/images/where-we-work-parallax.jpg);
            padding: 200px 300px;
            margin-bottom: 0px;
            background-repeat: no-repeat;
            background-size: cover;
            
        

        h2{
            color: white;
            text-align: center;
            text-transform: uppercase;
        }

        .linea{
            border-bottom: 1px solid #ffffff;
            width: 170px;
            margin: auto;
            margin-top: 30px;
            margin-bottom: 40px;
        }

        p{
            color: white;
            line-height: 30px;
            font-size: 18px;
            text-align: center;
            font-weight: bold;
        }

        .pulsante{
            display: flex;
            justify-content: center;
            margin-top: 30px;

            button{
                background-color: #61aca5;
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
                background-color: #6bc0b8;
            }
        }
    }
</style>