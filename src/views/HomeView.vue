<template>
  <div class="home">
    <JumbotronCom />

    <section id="contents">
      <AsideVue />
      <FeedVue />
      <AsideVue />

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