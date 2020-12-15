<template>
  <div>
    <div class="Header bg-white px-5">
      <router-link tag="div" :to="'./'">
        <Head />
      </router-link>
    </div>
    <Navigator class="Navi"/>
    <router-view/>
    <div class="body-main foot">
      <SchoolBadge />
    </div>
  </div>
</template>

<script>
import Head from './../components/Head.vue'
import Navigator from './../components/Navigator.vue'
import SchoolBadge from "./../components/SchoolBadge.vue";
export default {
  name: "app",
  components: {
    SchoolBadge,
    Head,
    Navigator
  }
};
</script>

<style>
.Header{
  margin: auto;
  max-width: 1366px;
  min-width: 1050px;
}
.Navi{
  margin: auto;
  max-width: 1366px;
  min-width: 1050px;
}
.foot{
  margin: auto;
  max-width: 1366px;
  min-width: 1050px;
}
</style>