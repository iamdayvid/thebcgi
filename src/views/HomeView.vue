<template>
  <div class="home">
    <JumbotronCom />
  </div>
</template>

<script>
// @ is an alias to /src
import JumbotronCom from '@/components/Jumbotron.vue'

export default {
  name: 'HomeView',
  components: {
    JumbotronCom,
  }
}
</script>
