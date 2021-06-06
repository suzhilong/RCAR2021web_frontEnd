<template>
  <div class="home bg-white px-2">
    <div class="msg">
        <h1 class="cmt-h1" style="margin-left:20px;">Call For Sponsor/Exhibitio</h1>
        <CfSE />
    </div>
  </div>
</template>


<script>
import Vue from "vue";
import CfSE from "../components/CfSE.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "CallForSponsorNExhib",
  components: {
    CfSE,
  },
};
</script>

<style>
.table{
  width: 800px;
  margin:auto;
}
</style>
