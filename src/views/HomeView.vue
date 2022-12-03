<template>
  <div class="home">
    <!-- Banner or Jumbotron -->
    <JumbotronCom />

    <section id="contents">
      <!-- Worship with Us Component -->
      <AsideVue heading="Worship With US" />

      <!-- Main Feed -->
      <FeedVue />

      <!-- Upcoming Events Component -->
      <AsideVue 
        heading="Upcoming Events" 
        msg="loremahhhhh"
        />

    </section>
  </div>
</template>

<script>
// @ is an alias to /src
import JumbotronCom from '@/components/Jumbotron.vue'
import AsideVue from '@/components/Aside.vue';
import FeedVue from '@/components/Feed.vue';

export default {
  name: 'HomeView',
  components: {
    JumbotronCom,
    AsideVue,
    FeedVue
  }
}
</script>
<style scoped lang="scss">
  #contents{
    display: flex;
    padding: 20px 20px 0px;
  }
</style>