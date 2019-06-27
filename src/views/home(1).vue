<template>
  <div class="home">
    <div class="header">
      <img src="../images/logo@2x.png">
      <div class="nav">
        <span>首页</span>
        <span>新闻</span>
        <span>团队</span>
        <span>白皮书</span>
        <span>关于</span>
      </div>
    </div>
    <div class="navction">
      <p>BCLS</p>
      <p>全球首个去中心化知识服务平台</p>
    </div>
    <div class="details">
      <img src="../images/beijing01@2x.png">
      <div class="prc">
        <p>区块链首个知识服务垂直应用</p>
        <p>高筑的区块链门槛让大多数门外人望而却步，为了体现区块链这个场站在风口浪尖上的更迭技术更新革命，提倡全名学习，持续学习的社区宗旨，让更多的人对区块链重识信心，为区块链信任降低门槛，特举行区块链小姐姐房车全球行的直播商业活动。宗旨在宣传、解读、了解拥抱区块链，让更多的人正确参与区块链拥抱区块链。</p>
      </div>
    </div>
    <div class="title">
      <img src="../images/jiejuetongdian@2x.png">
      <h2>解决痛点</h2>
    </div>
    <div class="sty">
      <span>学不会？</span>
      <span>学不全？</span>
      <span>学不起？</span>
      <span>不想学？</span>
    </div>
    <div class="study">
      <p><em></em>学不会： 优质内容+社区化交流+碎片化时间轻松解决学不会难题</p>
      <br/>
      <p><em></em>学不会： 优质内容+社区化交流+碎片化时间轻松解决学不会难题</p>
          <br/>
      <p><em></em>学不会： 优质内容+社区化交流+碎片化时间轻松解决学不会难题</p>
          <br/>
      <p><em></em>学不会： 优质内容+社区化交流+碎片化时间轻松解决学不会难题</p>
    </div>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="scss" scoped>
.header {
  height: 88px;
  line-height: 88px;
  img {
    margin-left: 100px;
    float: left;
    padding-top: 8px;
  }
  .nav {
    float: left;
    margin-left: 280px;
    span {
      width: 100px;
      display: inline-block;
      text-align: center;
      font-size: 16px;
    }
  }
}
.navction {
  background: url("../images/beijing@2x.png") no-repeat;
  background-size: 100% 100%;
  width: 100%;
  height: 450px;
  p:nth-child(1) {
    font-size: 90px;
    text-align: center;
    color: #ffffff;
    padding-top: 50px;
  }
  p:nth-child(2) {
    font-size: 32px;
    text-align: center;
    color: #ffffff;
  }
}
.details {
  height: 450px;
  img {
    float: right;
    width: 50%;
  }
  .prc {
    float: left;
    width: 50%;
    padding-top: 10%;
    p:nth-child(1) {
      background: url("../images/biaoqianyangshi@2x.png") no-repeat;
      background-size: 100% 100%;
      height: 50px;
      line-height: 50px;
      font-size: 18px;
      margin-left: 40px;
    }
    p:nth-child(2) {
      font-size: 12px;
      color: #999999;
      margin-left: 40px;
      line-height: 24px;
      padding-top: 30px;
    }
  }
}
.title {
  margin-left: 40px;
  height: 50px;
  display: block;
  img {
    width: 4%;
    float: left;
  }
  h2 {
    float: left;
    padding: 10px 0 0 10px;
    font-weight: 600;
    color: #000000;
  }
}
.sty {
  margin-left: 80px;
  display: block;
  height: 300px;
  span:nth-child(1) {
    background: url("../images/quan1@2x.png") no-repeat;
    background-size: 100% 100%;
    margin-top: 100px;
    width: 100px;
    height: 100px;
    padding-left: 8px;
    line-height: 100px;
    text-align: center;
    font-size: 16px;
    float: left;
  }
  span:nth-child(2) {
    background: url("../images/quan2@2x.png") no-repeat;
    background-size: 100% 100%;
    margin-left: 166px;
    width: 100px;
    padding-left: 8px;
    height: 100px;
    line-height: 100px;
    text-align: center;
    font-size: 16px;
    float: left;
  }
  span:nth-child(3) {
    background: url("../images/quan3@2x.png") no-repeat;
    background-size: 100% 100%;
    float: left;
    margin-top: 100px;
    margin-left: 90px;
    padding-left: 8px;
    width: 100px;
    height: 100px;
    line-height: 100px;
    text-align: center;
    font-size: 16px;
  }
  span:nth-child(4) {
    background: url("../images/quan4@2x.png") no-repeat;
    background-size: 100% 100%;
    float: left;
    margin-left: 166px;
    width: 100px;
    height: 100px;
    line-height: 100px;
    padding-left: 8px;
    text-align: center;
    font-size: 16px;
  }
}
.study{
  float: left;
  margin-left:80px;
  margin-top: 30px;
  font-size:12px;
  p{
    padding-top: 5px;
  }
  em{
    width: 5px;
    height:5px;
    display: inline-block;
    border-radius: 50%;
    background: blue;
        margin: 3px;
  }
}
</style>
