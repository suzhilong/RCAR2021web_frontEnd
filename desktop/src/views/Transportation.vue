<template>
  <div class="aboutXining home bg-white px-2">
      <div class="msg">
          <h1 class="cmt-h1" style="margin-left:20px;">Transportation</h1>
          <Trans />
      </div>
    </div>
</template>


<script>
import Vue from "vue";
import Trans from "./../components/Trans.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "Transport",
  components: {
    Trans,
  },
};
</script>

<style>

</style>