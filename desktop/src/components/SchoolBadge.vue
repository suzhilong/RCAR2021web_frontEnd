<template>
<div class="text-center bg-white py-3">
  <div class="d-flex jc-around ai-center " style="max-width:800px; margin:auto">
    <div v-for="logo in logos" :key="logo">
      <img :src="logo" alt style="max-height:50px"/>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      logos: [
        require("./../../../src/icons/01.png"),
        require("./../../../src/icons/02.png"),
        require("./../../../src/icons/03.png"),
        require("./../../../src/icons/AIRS_logo.png"),
        require("./../../../src/icons/qh.jpg"),
        require("./../../../src/icons/05.png"),
        require("./../../../src/icons/06.png"),
        require("./../../../src/icons/10.jpg"),
        require("./../../../src/icons/jn.jpg")
      ]
    };
  }
};
</script>

<style>
</style>