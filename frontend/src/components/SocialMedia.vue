<template>
  <div class="social">
    <p>{{ msg }}</p>
    <h1>SocialMedia Component</h1>
  </div>
</template>

<script>
export default {
  name: 'social-media',
  props: {
    msg: String
  }
}
</script>
