<template>
  <div class="home">
    <div class="share-button-container">
      <facebook-share-button />
    </div>
  </div>
</template>

<script>

import FacebookShareButton from '../components/FacebookShareButton.vue';

export default {
  name: 'Home',
  components: {
    FacebookShareButton,
  }
}
</script>

<style scoped>

.share-button-container {
  padding-top: 4rem;
}

</style>
