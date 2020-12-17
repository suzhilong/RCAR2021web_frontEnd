<template>
  <div class="aboutXining home bg-white px-2">
      <div class="msg">
          <h1 class="cmt-h1" style="margin-left:20px;">Venues</h1>
          <VenueData />
      </div>
    </div>
</template>


<script>
import Vue from "vue";
import VenueData from "./../components/VenueData.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "Venues",
  components: {
    VenueData,
  },
};
</script>

<style>

</style>