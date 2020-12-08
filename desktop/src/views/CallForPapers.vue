<template>
  <div class="fs-xxl">
    <h4 class="pt-2 text-center">
      Important Dates
      <i class="el-icon-date el-icon--right"></i>
    </h4>
    <el-row type="flex" class="row-bg" justify="space-around">
      <el-col :span="7.5">
        <div class="grid-content bg-purple"></div>
      </el-col>
    </el-row>
    <div class="mx-5 text-center">
      <TimeTable />
    </div>
    <div class="msg bg-white px-2" style="background-color:White;">
        <h1 style="margin-left:20px;">Call For Papers</h1>
        <Cfp />
    </div>

  </div>
</template>


<script>
import Vue from "vue";
import Cfp from "./../components/Cfp.vue";
import TimeTable from "./../components/TimeTable.vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "CallForPapers",
  components: {
    Cfp,
    TimeTable,
  },
};
</script>

<style>
.Cfp {
  max-width: 1366px;
  margin:auto;
}
</style>
