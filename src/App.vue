<script>
import AppHeader from './components/AppHeader.vue';
import axios from 'axios';

export default {
  data() {
    return {
    }
  }, components: {
    AppHeader
  }
}


</script>



<template>
  <header>
    <AppHeader />
  </header>

  <router-view></router-view>
</template>

<style scoped></style>
