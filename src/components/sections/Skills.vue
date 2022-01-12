<template>
  <div class="container">
          <div class="box">
            <div class="icon primary-color">
                <i class="fas fa-check"></i> 
            </div>
            <h3>a global view</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis.</p>
          </div>

          <div class="box">
            <div class="icon primary-color">
                <i class="fas fa-check"></i> 
            </div>
            <h3>expert lawyers</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis.</p>
          </div>

          <div class="box">
            <div class="icon primary-color">
                <i class="fas fa-check"></i> 
            </div>
            <h3>client focus</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis.</p>
          </div>

          <div class="box">
            <div class="icon primary-color">
                <i class="fas fa-check"></i> 
            </div>
            <h3>local knowledge</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime blanditiis perspiciatis.</p>
          </div>

    </div>
</template>

<script>

export default {
    name: 'Skills'
}
</script>

<style lang="scss" scoped>
    .container{
        max-width: 1080px;
        
        .icon{
            display: flex;
            justify-content: center;
            margin-bottom: 15px;
            font-size: 24px;
            
        }

        .box{
        padding: 40px 30px 48px;
        }

        .box:hover{
            cursor: pointer;
            h3{
                color: #55a098;
            }
        }
    }

</style>