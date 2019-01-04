<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <SocialMedia msg />
  </div>
</template>

<script>
// @ is an alias to /src
import SocialMedia from '@/components/SocialMedia.vue'

export default {
  name: 'home',
  components: {
    SocialMedia
  }
}
</script>
