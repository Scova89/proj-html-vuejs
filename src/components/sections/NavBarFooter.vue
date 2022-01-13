<template>
  <div class="list-container">
    <ul class="secondary-font">
      <li><a :href="link.state">{{link.text}}</a></li>
    </ul>
  </div>
</template>

<script>
export default {
    name: 'NavBarFooter',
    props: {
      link: Object
    }
}
</script>

<style lang="scss" scoped>
    ul{
        list-style: none;
        display: flex;
        font-size: 14px;
        li{
        padding: 6px ;

        a{
            text-decoration: none;
            color: #838b8e;
            cursor: pointer;
        }
        }
    }
</style>