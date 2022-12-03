<template>
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
        flex-basis: 500px;
        flex-grow: 199;
        min-height: 250px;
        background-color: antiquewhite;
    }

</style>