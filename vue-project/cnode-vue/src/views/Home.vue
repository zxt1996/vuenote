<template>
  <div class="home">
    <Header/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/header.vue'

export default {
  name: 'home',
  components: {
    Header
  }
}
</script>
