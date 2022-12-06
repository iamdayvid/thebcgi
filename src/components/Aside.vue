<template>
    <!-- Aside Component -->
    <section class="aside">
        <h2>{{heading}}</h2>
        <p>{{msg}}</p>
    </section>
</template>
<script>

export default{
    name: "AsideComponent",
    props: {
        heading: String,
        msg: String,
        title: String,
        startDate: String,
        EndDate: String
    }
}
</script>
<style scoped lang="scss">
    .aside{
        // width: 300px;
        
        min-height: 250px;
        max-height: 700px;
        background-color: antiquewhite;
    }

</style>