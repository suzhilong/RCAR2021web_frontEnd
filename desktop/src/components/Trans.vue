<template>
  <div class="fs-xxl msg">
    <h2 class="cmt-p">By Air</h2>
    <p class="cmt-p">Xining Caojiapu International Airport has domestic flights to Beijing Daxing International Airport, and Beijing Capital International Airport. International flights go to Kuala Lumpur, and Nha Trang. Xining Caojiapu International Airport is a 30 to 40-minute taxi ride from Xining Railway Station.</p>
    <h2 class="cmt-p">By Train</h2>
    <p class="cmt-p">Xining Railway Station links to Lanzhou on bullet train. The tourists can transfer to high-speed rail to Beijing, Shanghai, and Guangzhou.</p>
    <h2 class="cmt-p">From Beijing to Xining by Train</h2>
    <p class="cmt-p">The trip takes around 11 hours. From Beijing West Railway Station, the tourists can take the high-speed rail to Lanzhou then transfer to the bullet train for Xining.</p>
    <div class="images-mid">
      <img src="../../../src/images/transport.jpg" class="transport">
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
  .el-row {
    margin-bottom: 10px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .images-mid{
    margin-left:50px;
    margin-right:50px;
  }
  .transport{
    width: 960px;
    /* height: 1080px; */
  }
  .cmt-h3{
    font-family:Arial, Helvetica, sans-serif;
    font-weight: bold;
    margin-left:50px;
    margin-top:30px;
  }
  .cmt-p{
    font-family:Arial, Helvetica, sans-serif;
    margin-left: 50px;
    margin-right: 50px;
  }
  .msg {
    width: 1288px;
    /* max-width: 1200px;
    min-width: 1050px; */
    margin: auto;
  }
</style>