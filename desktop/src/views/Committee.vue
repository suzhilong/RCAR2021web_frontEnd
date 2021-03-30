<template>
  <div class="home bg-white px-2" style="background-color:White;">
    <div class="msg">
      <h1 class="cmt-h1">Committee</h1>
      <Committees/>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import Committees from "./../components/Committees.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "CallForPapers",
  components: {
    Committees,
  },
};
</script>

<style>
.cmt-h1{
    color:rgb(0,102,204);
    font-family:Arial, Helvetica, sans-serif;
    font-weight: bold;
    margin-left:50px;
}
</style>