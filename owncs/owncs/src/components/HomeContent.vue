<template>
  <v-container fluid fill-height class="home-content">
    <v-layout justify-center align-center column pa-5>
      <div class="display-4 font-weight-black white--text text-xs-center mb-3">
        OWNCS
      </div>
      <div class="display-1 font-weight-black white--text text-xs-center mb-3">
        Our World Neighborhood Charter School
      </div>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'HomeContent'
};
</script>

<style scoped>
.home-content {
  background: url('https://images.unsplash.com/photo-1547158944-a757fd11c576?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2111&q=80');
  background-size: cover;
  width: 100%;
  height: 100%;
}
</style>
