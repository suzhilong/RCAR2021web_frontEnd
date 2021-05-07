<template>
  <div class="aboutXining home bg-white px-2">
      <div class="msg">
          <h1 class="cmt-h1" style="margin-left:20px;">Accommodation</h1>
          <AccommodationData />
      </div>
    </div>
</template>


<script>
import Vue from "vue";
import AccommodationData from "./../components/AccommodationData.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "Accommodation",
  components: {
    AccommodationData,
  },
};
</script>

<style>

</style>