<template>
  <span>
    <v-container
      fluid
      fill-height
      class="home-hero hidden-sm-and-down"
      style="max-height: 100vh;"
    >
      <v-layout
        justify-start
        row
      >
        <v-flex
          md5
          class="offset-md1"
        >

        </v-flex>
      </v-layout>
    </v-container>
    <v-container class="hidden-md-and-up" />
  </span>
</template>

<script>
export default {
  name: 'HomeHero',
  components: {}
}
</script>

<style scoped>
.home-hero {
  /*background: url('https://kit.edu.kh/assets/images/slider/slider1.jpg');*/
  /*background: url('https://kit.edu.kh/assets/images/slider/slider3.jpg');*/
  background: url('https://kit.edu.kh/assets/images/slider/slider2.jpg');
  background-size: cover;
  width: 100%;
  height: 100%;
  margin-top: -70px;
  padding-top: 70px;
}
</style>
