<template>
  <div class="home">
    <mangaDetail></mangaDetail>
  </div>
</template>

<script>
// @ is an alias to /src
import mangaDetail from '@/components/mangaDetail.vue'

export default {
  name: 'HomeView',
  components: {
    mangaDetail
  }
}
</script>
