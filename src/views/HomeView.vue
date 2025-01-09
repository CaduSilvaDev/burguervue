<template>
  <BannerComponent />
  <div class="main-container">
    <h1>Monte o seu burger</h1>
    <p>Formulário</p>
  </div>
</template>

<script>
import BannerComponent from '../components/BannerComponent.vue';

export default {
  name: 'HomeView',
  components: {
    BannerComponent
  }
}
</script>
