<template>
  <header id="header">
    <div id="logo">
      <router-link to="/"><img src="./assets/thebgci-logo-800.png" alt="The Beautiful Garden Church International"></router-link>
    </div>
    <nav id="nav">
      <router-link to="/" class="home">Home</router-link>
      <router-link to="/about" class="about">About</router-link>
    </nav>
  </header>
  <main>
    <router-view/>
  </main>
</template>

<style lang="scss">
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
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
