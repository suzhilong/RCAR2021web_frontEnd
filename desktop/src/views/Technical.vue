<template>
  <div class="home body-main border-body bg-white ql-align-articles px-3">
      <h1 span style="color:rgb(0,102,204)">
        Technical Sessions
      </h1>
      <br>
      <!-- <h1 align="center">Coming Soon...</h1> -->
      <!-- <h4>
        <font>
             <a href="http://www.ieee-rcar.com/uploads/IEEE_RCAR_2020_Technical_Session.pdf" target="_blank" style="background-color:transparent;color: rgb(250,0,0);">Click here to download the detailed program of Technical Session in PDF</a>
        </font>
      </h4> -->
      <div class="glance">
      <!-- <img src="./../../../src/images/TechnicalSessions.png" class="card-im-left" width="100%"> -->
      <img src="./../../../src/images/session15.png" width="80%">
      <img src="./../../../src/images/session16.png" width="80%">
      <img src="./../../../src/images/session17.png" width="80%">
      <img src="./../../../src/images/session18_19.png" width="80%">
      </div>
  </div>
</template>

<script>
import Vue from "vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "home",
  component:{
  }
};
</script>

<style>
.home {
  max-width: 1366px;
  margin:auto;
}
.msg {
  max-width: 1200px;
  margin: auto;
}
.glance{
  margin-left: 10%;
}
/* .el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center; 
     margin-left: 10%;
    width:80%;
  } */

.el-main {
  text-align: justify;
}
</style>
