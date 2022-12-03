<template>
  <div id="banner">
   <img src="../assets/theme-of-the-year-desktop.jpg" alt="The Theme of the Year Banner">
  </div>
</template>

<script>
export default {
  name: 'JumbotronCom',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#banner{
  width: 100%;
  height: 512px;
  // background-image: url("../assets/theme-of-the-year.jpg");
  // background-size: cover;
  // // background-repeat: no-repeat;
  // background-position: center;
  

  img{
    width: inherit;
    height: inherit;
  }
}

</style>
