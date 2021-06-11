<template>
  <div class="home body-main border-body bg-white ql-align-articles px-3">
      <h1 span style="color:rgb(0,102,204)">
        Keynote Speakers
      </h1>
      <br>
      <!-- <h1 align="center">Coming Soon...</h1> -->
      <h3 style="margin-top:10px; margin-bottom:10px;">
        <strong> Keynote Talk Ⅰ
          <!-- : 13:00-13:30, Monday, Sep. 28 -->
          </strong>
      </h3>
      <br>
      <!-- <img src="./../../../src/images/XiangpengLi.png" class="card-im-left" width="175" height="222"> -->
      <br>
      <h4>
        <strong> Prof. </strong>
      </h4>
      <h4>
        <strong>Title: </strong>
      </h4>
      <h5>
      <p style="text-align:justify">
        <strong>Abstract:</strong>
        
      </p>
      <p style="text-align:justify">
        <strong>Biography:</strong>
        
        </p>
      </h5>

      <br>
      <h3 style="margin-top:10px; margin-bottom:10px;">
        <strong> Keynote Talk II
          <!-- : 13:30-14:00, Monday, Sep. 28 -->
          </strong>
      </h3>
      <br>
      <img src="./../../../src/images/2DongWang.png" class="card-im-left" width="175" height="222">
      <br>
      <h4>
        <strong> Prof. Dong Wang, Dalian University of Technology, China</strong>
      </h4>
      <h4>
        <strong>Title: Distributed Optimization based on multiagent systems</strong>
      </h4>
      <h5>
      <p style="text-align:justify">
        <strong>Abstract:</strong>
        In the past years, distributed optimization based on multiagent systems has received considerable attention due to its wide applications in smart grid, resource allocation and machine learning. Common features of these examples are that there is no centralized center involved and the resources, such as sensing, communication and computation, are usually connected by the networks and communicate in the local networks, which is called distributed algorithms. In this talk, I will first give some concepts related to distributed optimization and communication model. Then, I will introduce several recent works on distributed optimization. Application to economic dispatch problems in smart grids will also be discussed.
      </p>
      <p style="text-align:justify">
        <strong>Biography:</strong>
        Dong Wang received the B.Sc. degree in automation and the M. Eng. degree in control theory and control engineering from the Shenyang University of Technology, Shenyang, China, in 2003 and 2006, respectively, and Ph.D. degree in control theory and control engineering from the Dalian University of Technology, China, in 2010. Since 2010, he has been with the Dalian University of Technology, where he is currently a professor with the School of Control Science and Engineering. His current research interests include multiagent systems, distributed optimization, fault detection and switched systems. He is the author or co-author of over 100 publications, which have been appeared in IEEE Transactions Journals and in conference proceedings. He is appointed as the 2019 Changjiang Young Scholars programs and was a recipient of the second prize of Wuwenjun Artificial Intelligence Science and Technology in 2017. Dr. Wang is Associate Editors of Information Sciences and Neurocomputing.
        </p>
      </h5>

      <br>
      <h3 style="margin-top:10px; margin-bottom:10px;">
        <strong> Keynote Talk III
          <!-- : 13:00-13:30, Tuesday, Sep. 29 -->
          </strong>
      </h3>
      <br>
      <!-- <img src="./../../../src/images/SONGZhan.png" class="card-im-left" width="175" height="222"> -->
      <br>
      <h4>
        <strong> Prof. </strong>
      </h4>
      <h4>
        <strong>Title: </strong>
      </h4>
      <h5>
      <p style="text-align:justify">
        <strong>Abstract:</strong>
        
      </p>
      <p style="text-align:justify">
        <strong>Biography:</strong>
        
        </p>
      </h5>

      <br>
      <h3 style="margin-top:10px; margin-bottom:10px;">
        <strong> Keynote Talk IV
          <!-- : 13:30-14:00, Tuesday, Sep. 29 -->
          </strong>
      </h3>
      <br>
      <!-- <img src="./../../../src/images/LinWang.jpg" class="card-im-left" width="175" height="222"> -->
      <br>
      <h4>
        <strong> Prof. </strong>
      </h4>
      <h4>
        <strong>Title: </strong>
      </h4>
      <h5>
      <p style="text-align:justify">
        <strong>Abstract:</strong>
        
      </p>
      <p style="text-align:justify">
        <strong>Biography:</strong>
        
        </p>
      </h5>


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
