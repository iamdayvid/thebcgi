<template>
    <header id="header">
        <div id="logo">
            <router-link to="/"><img src="../assets/thebgci-logo-800.png"
                    alt="The Beautiful Garden Church International"></router-link>
        </div>
        <div id="search">
            <label for="search">Search</label>
            <input type="search" name="search" id="input-search">
        </div>
        <nav id="nav">
            <router-link to="/" class="home">Home</router-link>
            <router-link to="/events" class="home">Events</router-link>
            <router-link to="/about" class="about">About</router-link>
        </nav>
    </header>
</template>
<script>

export default{
    name: "NavBar"
}

</script>

<style lang="scss">
#hearder{
    
}
</style>