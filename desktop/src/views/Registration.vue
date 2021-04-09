<template>
  <div class="home border-body bg-white ql-align-articles px-3">
    <h1 align="center">Coming Soon...</h1>
    <!--
    <h1 span class = "cmt-h1">
      Registration
    </h1>
    <h4 class = "regis">
      Important Notes:
    </h4>
    <h5 class = "regis">
    <ul>
      <li>There are no special discounts for any types of registrations. The registration fee is 
        <strong>
        $100
        </strong>
          for all attendees. The fee include admission to final paper uploading, technical sessions, workshops and tutorials, the conference proceedings. </li>
      <li>For one submission, it should be ensured that one of the authors can finish the registration as the presenter before the event. For other attendees except the presenter, it is 
        <strong>
        free
        </strong>
        . Therefore only one registration is necessary for each accepted paper. </li>
      <li>For the final submissions which length is beyond 6 pages, an additional surcharge of 
        <strong>
          $100 per extra page
        </strong>
            has to be paid. </li>
      <li>Registration is required to be finished before 
        <font color="#FF0000">
        Xxx. xx, 2021.
        </font>
        </li>
    </ul>
    </h5>
    <h4 class = "regis" style="margin-top:0px; margin-bottom:20px;text-decoration: underline;">
      <strong>
        <font color="FF0000">
            <a href="https://suzhilong.github.io/2021/03/30/rcar_wiki/" target="_blank" style="background-color:transparent;color: rgb(220,20,60);">Registration procedure is here</a>
        </font>
      </strong>
    </h4>
    <h4 class = "regis">
      Cancellation Policy
    </h4>
    <h5 class = "regis">
    <ul>
      <li>In any cases, no refunds will be made if your registration is used to upload your final submission(s) for RCAR 2021.</li>
      <li>To cancel your registration, please notify the secretariat by Email: 
        <a href="mailto:ieee.rcar@gmail.com" rel="noopener noreferrer" target="_blank" style="background-color:transparent;color:rgb(51,122,183);">ieee.rcar@gmail.com.</a></li>
    </ul>
    </h5>
    <br> 
    -->
    <!-- 微信群 -->
    <!-- <h5 class = "regis">
      Join RCAR 2021 WeChat Group!
    </h5>
    <div>
      <img src="./../../../src/images/20200925145023.jpg" width="200" height="200">
    </div> -->
  </div>
</template>

<script>
import Vue from "vue";
import { ImagePlugin } from "bootstrap-vue";
Vue.use(ImagePlugin);
export default {
  name: "home",
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

.regis {
  margin-left:50px;
}

.el-main {
  text-align: justify;
}
</style>