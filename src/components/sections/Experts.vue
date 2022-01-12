<template>
    <div class="expert-container bg-primary-color">
        <div class="container">
            <h2>QUESTIONS ABOUT A JUDICIAL ISSUE? ASK OUR EXPERTS.</h2>
            <div class="pulsante">
              <button class="primary-font">learn more</button>
            </div>
        </div>
        

    </div>
  
</template>

<script>
export default {
    name: 'Experts'
}
</script>

<style lang="scss" scoped>
    .expert-container{
        color: white;
        display: flex;
        justify-content: center;
        padding-top: 72px;
        margin-top: 0px;
        padding-right: 30px;
        padding-bottom: 52px;
        margin-bottom: 0px;
        padding-left: 30px;

        .container{
            align-items: center;
            justify-content: space-between;
            
        }

        .pulsante{
            display: flex;
            justify-content: center;

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