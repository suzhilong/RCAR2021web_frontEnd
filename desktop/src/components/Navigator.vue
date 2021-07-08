<template>
  <el-menu
    class="el-menu-rcar fw-xxl"
    mode="horizontal"
    background-color="rgb(6, 17, 114)"
    text-color="#FFF"
    active-text-color="rgb(220, 220, 220)"
    router
  >
    <el-menu-item index="./">
      <template slot="title">
        <!-- <p class="el-icon-house pt-2"></p> -->
        Home
      </template>
    </el-menu-item>

    <el-menu-item index="./Committee">
      <template slot="title">Committee</template>
    </el-menu-item>

    <!-- 把disabled删掉就可以激活 -->
    <el-submenu index="2">
      <template slot="title">Program</template>
      <el-menu-item index="./Program" >Program at a Glance</el-menu-item>
      <el-menu-item index="./Plenary" >Plenary Speakers</el-menu-item>
      <el-menu-item index="./Keynote" >Keynote Speakers</el-menu-item>
      <el-menu-item index="./Technical" >Technical Sessions</el-menu-item>
      <el-menu-item index="./Proceedings" >Proceedings</el-menu-item>
    </el-submenu>
   
    <!-- <el-menu-item index="./CallForPapers">
      <template slot="title">Call for Papers</template>
    </el-menu-item> -->

    <el-submenu index="3">
      <template slot="title">Call For</template>
      <el-menu-item index="./CallForPapers" >Call For Papers</el-menu-item>
      <el-menu-item index="./CallForSponsorExhibition" >Call For Sponsor/Exhibition</el-menu-item>
    </el-submenu>

    <!-- 把disabled删掉就可以激活 -->
    <el-submenu index="4">
      <template slot="title">Submission</template>
      <el-menu-item index="./InitialSubmission">Initial Submission</el-menu-item>
      <el-menu-item index="./FinalSubmission">Final Submission</el-menu-item>
    </el-submenu>

    <el-submenu index="5">
      <template slot="title">Venue</template>
      <el-menu-item index="./Venue">Venues</el-menu-item>
      <el-menu-item index="./Accommodation">Accommodation</el-menu-item>
    </el-submenu>

    <el-submenu index="6">
      <template slot="title">Travel</template>
      <el-menu-item index="./AboutXining">About Xining</el-menu-item>
      <el-menu-item index="./Transportation">Transportation</el-menu-item>
    </el-submenu>

    <el-menu-item index="./Registration">
      <template slot="title">Registration</template>
    </el-menu-item>

    <!-- <el-menu-item index="./CallForSponsorExhibition">
      <template slot="title">Call For Sponsor/Exhibition</template>
    </el-menu-item> -->

    <el-menu-item index="./history">
      <template slot="title">History</template>
    </el-menu-item>

    <el-menu-item>
      <template slot="title">
        <p class="el-icon-question pt-2"></p>
        <a href="">
          FAQ
        </a>
      </template>
    </el-menu-item>

  </el-menu>
</template>

<script>
export default {};
</script>

<style lang="scss">
.el-menu {
  position: sticky;
  top: 0;
  z-index: 999;
  font-family: Arial, Helvetica, sans-serif;
}
.el-menu-item {
  font-size: 16px !important;
  font-family: Arial, Helvetica, sans-serif;
}
.el-submenu__title {
  font-size: 16px !important;
  font-family: Arial, Helvetica, sans-serif;
}

</style>
