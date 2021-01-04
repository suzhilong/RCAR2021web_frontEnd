<template>
  <div class="body-main">
    <div class="msg bg-white px-5">
      <!-- <h1 align="center">Coming Soon...</h1> -->
      <!-- 取消注释就可以用了 -->
      <InitialBody />
    </div>
  </div>
</template>


<script>
import InitialBody from "./../components/InitialBody.vue";
export default {
  name: "InitialSub",
  components: {
    InitialBody,
  },
};
</script>

<style>
</style>