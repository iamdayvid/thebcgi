<template>
  <NavBarVue />
  <main>
    <router-view/>
  </main>
  <FooterVue />
</template>
<script>
import NavBarVue from './components/NavBar.vue';
import FooterVue from './components/Footer.vue'

export default{
  name: "App",
  components: {
    NavBarVue,
    FooterVue
  }
}

</script>

<style lang="scss">
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

a{
  text-decoration: none;
  color: #000;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  // color: #2c3e50;

  #header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    // background-color: aquamarine;
    padding: 10px 20px;

    #logo{

      img{
        width: 70px;
        height: 70px;
        border-radius: 50%;
      }
    }

    #nav{
      .home{
        margin-right: 20px;
      }
    }
  }
}
</style>
