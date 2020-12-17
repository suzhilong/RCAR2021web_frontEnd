<template>
  <div class="aboutXining home bg-white px-2">
      <div class="msg">
          <h1 class="cmt-h1" style="margin-left:20px;">About Xining</h1>
          <Xining />
      </div>
    </div>
</template>


<script>
import Vue from "vue";
import Xining from "./../components/Xining.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "AboutXining",
  components: {
    Xining,
  },
};
</script>

<style>

</style>