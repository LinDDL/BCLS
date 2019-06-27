<template>
  <div class="home" id="home">
    <div class="header">
      <img src="../images/logo@2x.png">
      <div class="nav">
        <span> <a href="#home">首页</a> </span>
        <span><a href="#xw">新闻</a> </span>
        <span><a href="#td"> 团队</a></span>
        <span><a class="bp" :href="'../assets/BCLS白皮书1.0版(1).pdf'" > 白皮书</a></span>
        <span><a href="#gy">联系我们</a> </span>
      </div>
    </div>
    <div class="navction clearfloat">
       <p>BCLS</p>
      <p>全球首个去中心化知识服务平台</p>
    </div>
    <div class="details clearfloat">
      <div class="prc clearfloat" id="xw">
        <p>区块链首个知识服务垂直应用</p>
        <p>⾼筑的区块链门槛让⼤多数门外⼈望⽽却步，为了体现区块链这场站在风口浪尖上的更迭技术⾰命，提倡全民学习，持续学习的社区宗旨，让更多的⼈对区块链重拾信⼼，为区块链信任降低门槛，特举⾏区块链⼩姐姐房车全球⾏的直播商业活动。宗旨在宣传、解读、了解拥抱区块链，让更多的⼈正确参与区块链拥抱区块链。</p>
      </div>
      <img src="../images/beijing1@2x.png">
    </div>
    <div class="title clearfloat">
      <img src="../images/tongdian@2x.png">
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
      <p><em></em>学不全：专业类学科知识 + 综合类创业知识 +⼤大众类社科通识 + 专业类商业分享 +…. </p>
      <p><em></em>学不起：⾦钱成本与时间成本居⾼不下，通过区块链降低各⽅⾯成本</p>
      <p><em></em>不想学：游戏化学习⽅法激发⽤户学习星期</p>
    </div>
    <div class="clearfloat">
      <div class='group' id='td'>
        <img src="../images/tuandui@2x.png" >
        <span>团队</span>
      </div>
    </div>
    <div class="people clearfloat">
      <img class="left" src="../images/jiantou@2x.png" alt="">
      <div class="people-box">
        <img class="img1" src="../images/people1@2x.png" alt="">
        <h3>雷应秋</h3>
        <p>区块链房车小姐姐全球行联合发起人</p>
        <p>长城公社联合创始人</p>
        <p>兼全国公益大讲堂主持人，</p>
        <p>比特币忠实信仰者，</p>
        <p>区块链投资人布道者</p>
      </div>
      <div class="img2-box people-box">
        <img class="img2" src="../images/people2@2x.png" alt="">
        <h3>赵刚</h3>
        <p>区块链早期投资人</p>
        <p>国家高级区块链技术咨询师</p>
        <p>韩立电子科技有限公司董事长</p>
      </div>
      <div class="people-box">
        <img class='img1' src="../images/people3@2x.png" alt="">
        <h3>高朋</h3>
        <p>8分钟区块链创始人</p>
        <p>区块链早期从业者，</p>
        <p>天使投资人</p>
      </div>
      <img class="right" src="../images/jiantou1@2x.png" alt="">
    </div>
    <div class="program clearfloat">
      <img class='beijing1' src="../images/45@2x.png" alt="">
      <div class="program-box">
        <p class='program-title'>房车上的区块链实事评论节目</p>
        <p class="program-text">房车⼩姐姐以每周⼀期的动态评论节⽬为主打推广卖点节目以辛辣逗趣又附带干货的风格作为主调每期还会邀请房车路线途中知名的⼤咖作为嘉宾在各大⻔户⽹站及直播平台开设专栏或者直播间迅速扩⼤平台项目知名度</p>
        <img  class='beijing2' src="../images/xiaobeijing@2x.png" alt="">
      </div>
    </div>
    <div class='process'>
      <img src="../images/fazanxian@2x.png" alt="">
    </div>
    <div class="title" id="gy">
      <img src="../images/lianxiwomen@2x.png" alt="">
      <h2>联系我们</h2>
    </div>
    <div class="erweima">
       <img src="../images/erweima@2x.png" alt="">
      </div>
  </div>
</template>

<script>
  export default {

  }
</script>
<style lang="scss" scoped>
#home{
      position: relative;
}
 a {
   text-decoration:none ;
   color:rgba(0,0,0,1)
 }
.header {
  height: 40px;
  line-height: 40px;
  display: flex;
  flex-direction: "row";
  padding-left:40px;
  background:rgba(255,255,255,1);
  img {
    width:25px;
    height:35px;
  }
  .nav {
    flex:1;
    margin-left: 118px;
    display: flex;
    justify-content: space-around;
    a {
      font-size:13px;
      font-family:PingFang-SC-Medium;
      font-weight:500;
      color:rgba(0,0,0,1);
      line-height:17px;
    }
  }
}
.navction {
  background: url("../images/beijing.png") no-repeat center center;
  width: 100%;
  height: 600px;
  p:nth-child(1) {
    font-size: 157px;
    text-align: center;
    color: #ffffff;
    padding-top: 150px;
    margin-block-end: 0%;
    margin-block-start: 0%
  }
  p:nth-child(2) {
    font-size: 32px;
    text-align: center;
    color: #ffffff;
  }
}
.details {
  display: flex;
  img {
    width: 50%;
    height:50%;
  }
  .prc {
    width: 100%;
    padding-top: 10%;
    position: relative;
    p:nth-child(1) {
      border:1px dashed #bbb;
      background: url("../images/biaoqianyangshi@2x.png") no-repeat;
      background-size: 100% 100%;
      width:66%;
      padding:5% 0;
      font-weight: bold;
      font-size: 20px;
      margin-left: 40px;
    }
    p:nth-child(2) {
      font-size: 13px;
      text-align: left;
      margin-left: 40px;
      padding-top: 30px;
      width:110%;
      font-family:PingFang-SC-Light;
      font-weight:300;
      color:rgba(43,48,64,1);
      line-height:30px;
    }
  }
}
.title {
  height: 50px;
  display: block;
  padding-top: 5%;
  padding-left:40px;
  img {
    width: 4%;
    float: left;
  }
  h2 {
    float: left;
    font-size: 19px;
    font-family:PingFang-SC-Bold;
    margin-left: 18px;
    font-weight:bold;
    color:rgba(0,0,0,1);
    line-height:33px;
  }
}
.sty {
  display: inline-flex;
  height: 300px;
  width: 100%;
  margin-top: 4%;
  position: relative;
  padding:0 40px;
  span:nth-child(1) {
    display:block;
    background: url("../images/xuebuhui@2x.png") no-repeat center center;
    background-size: 100% 100%;
    position: absolute;
    top: 9%;
    left: 5%;
    margin-top:15%;
    width: 109px;
    height: 109px;
    padding-left: 8px;
    margin-top:6.5%;
    line-height: 109px;
    text-align: center;
    font-size: 21px;
    font-family:PingFang-SC-Medium;
    font-weight:500;
    color:rgba(29,29,29,1);
  }
  span:nth-child(2) {
    display:block;
    background: url("../images/xuebuquan@2x.png") no-repeat;
    background-size: 100% 100%;
    width: 110px;
    padding-left: 8px;
    position: absolute;
    top:0;
    left: 35%;
    height: 110px;
    line-height: 109px;
    font-size: 21px;
    font-family:PingFang-SC-Medium;
    color:rgba(255,255,255,1);
    font-weight:500;
  }
  span:nth-child(3) {
    display:inline-block;
    background: url("../images/xuebuqi@2x.png") no-repeat;
    background-size: 100% 100%;
    margin-top: 100px;
    margin-left: 19%;
    padding-left: 8px;
    width: 110px;
       position: absolute;
    top: 9%;
    left:42%;
    height: 110px;
    line-height: 110px;
    text-align: center;
    font-size: 21px;
    font-family:PingFang-SC-Medium;
    color:rgba(255,255,255,1);
    font-weight:500;
  }
  span:nth-child(4) {
    display:inline-block;
    background: url("../images/buxiangxue@2x.png") no-repeat;
    background-size: 100% 100%;
    margin-left: 15%;
    width: 110px;
    height: 110px;
    line-height: 110px;
       position: absolute;
    top:0;
    left:66%;
    padding-left: 8px;
    text-align: center;
    font-size: 21px;
    font-family:PingFang-SC-Medium;
    font-weight:500;
    color:rgba(255,255,255,1);
  }
}
.study{
  padding:0 40px;
  margin-top: 30px;
  font-size:12px;
  p{
    padding-top: 5px;
    text-align: left;
    margin-bottom: 37px;
    overflow: hidden;
    text-overflow:ellipsis;
    white-space: nowrap;
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
.group{
  float:right;
  margin-top:87px;
  margin-right:50px;
  clear: both;
  img{
    width:40px;
    height:38px;
    float: left;
  }
  span{
    float: left;
    margin-left:11px;
    margin-top:2px;
    font-size:19px;
    font-family:PingFang-SC-Bold;
    font-weight:bold;
    color:rgba(0,0,0,1);
    line-height:33px;
  }
}
.clearfloat:after{
  display:block;
  clear:both;
  content:"";
  visibility:hidden;height:0}
.people{
  margin-top:20px;
  padding:0 40px;
  display: flex;
  justify-content: space-around;
  .people-box{
    padding:0 5px;
  }
 .left,.right{
   width:17px;
   height:31px;
 }
 .left{
   margin-right: 4%;
   margin-top:15%;
 }
 .right{
   margin-left:4%;
   margin-top:15%;

 }
 .img1{
  width:170px;
  height:170px;
  background:rgba(187,14,14,1);
  border-radius:50%;
  margin-top:20px;
 }
 .img2{
   width:220px;
   height:220px;
   border-radius:50%;
 }

 h3{
    font-size: 16px;
    font-weight: 600;
    margin-top: 11px;
    color: #000000;
    margin-bottom:12px;
    font-family: 'PingFang-SC-Bold';
 }
 p{
   font-size: 12px;
   font-weight:bold;
   line-height: 30px;
   font-family: 'PingFang-SC-Medium';
   transform: scale(0.85);
 }
 }
.program{
  display: flex;
  justify-content: space-between;
   margin-top:46px;
   .program-box{
   }
  .program-text{
    font-size:13px;
    font-family:PingFang-SC-Light;
    font-weight:300;
    color:rgba(43,48,64,1);
    line-height:30px;
    text-align: left;
  }
 .beijing1{
   width:27%;
   height:600px;
 }
 .program-box{
   .program-title{
      background: url("../images/biaoqianyangshi@2x.png") no-repeat;
      background-size: 100% 100%;
      height: 65px;
      width:328px;
      font-weight: bold;
      line-height: 65px;
      font-size: 20px;
      margin:0 auto;
   }

 }
 .beijing2{
   width:85px;
   height:71px;
   float:right;
 }
}
.erweima{
   text-align:center;
  display: block;
  width: 100%;
  margin-bottom: 100px;
  img{
  margin: auto;
    width:244px;
    height:244px;
    text-align: center;
    display: block;
    margin-top: 5%;
    background:rgba(255,255,255,1);
    box-shadow:0px 1px 18px 0px rgba(0, 0, 0, 0.35);
  }
}
.ximg{
  width:41px;
  height:41px;
}
.process{
   width: 100%;
   margin-top: -5%;
   vertical-align: middle;
    text-align: center;
  img{
    width:80%;
    text-align: center;
    display: block;
    margin-left:10%;
  };

}

</style>
