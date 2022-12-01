<template>
    <footer id="footer">
        <div class="nav-links">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nulla, suscipit!
        </div>
        <div class="social-copyright">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit, repudiandae.
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed rem sint corporis quibusdam cumque repellendus unde iste laudantium consequuntur nam.
        </div>
        <div class="address">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure, commodi!
        </div>
    </footer>
</template>
<script>

export default{
    name: "FooterVue"
}

</script>
<style scoped lang="scss">
    #footer{
        display: flex;
        justify-content: space-between;

        div{
            height: 300px;
            padding: 20px;
            // width: 200px;
            background-color: rgb(20, 228, 38);
        }

        .nav-links{
            width: 200px;
        }

        .address{
            width: 200px;
        }
    }

</style>