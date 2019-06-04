<template>
  <span>
    <home-content></home-content>
    <home-details></home-details>
  </span>
</template>

<script>
import HomeContent from '@/components/HomeContent';
import HomeDetails from '@/components/HomeDetails';

export default {
  name: 'home',
  components: {
    HomeContent,
    HomeDetails
  }
};
</script>
