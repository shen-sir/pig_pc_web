<template>
  <div id="app">
    <div class="page1">
      <div class="top">
        <img src="./assets/dingbulogo.png" >
        <div class="text">
          <p>猪队友</p>
          <span>PIGYYMATE</span>
        </div>
      </div>
      <div class="context">
        <img src="./assets/iPhone-.png" class="left">
        <div class="right">
          <img src="./assets/zi.png" >
          <p>猪队友是为开黑陪玩的玩家所做的网游一站式服务社交平台。突破了目前互联网游戏平台功能过于单一这一局限性。
从开黑房间到大神陪玩再到贴吧论坛，猪队友包含了目前游戏圈所有玩家需求的功能。
让小猪陪你一起杀入战场吧！</p>
          <div class="btn iphone">苹果客户端下载</div>
          <div class="btn androd">苹果客户端下载<span></span></div>
        </div>
      </div>
    </div>
    <div class="page2">
      <div class="center">
        <div class="left">
          <img src="./assets/dierping.png">
        </div>
        <div class="right">
          <p class="name">猪队友 <strong>主页</strong> </p>
          <p class="describe">与小猪杀入战场吧</p>
          <p class="text">"猪队友" 是一款多功能社交开黑平台。玩家可以在右上角个人中心包装自己。</p>
          <p class="text">添加个性标签，上线匹配开黑队友或直接多人开黑。点击小猪上线与好友一起享受开黑乐趣吧。</p>
        </div>
      </div>
    </div>
    <div class="page3">
      <div class="center">
        <img src="./assets/disanping-tu.png">
        <div class="right">
          <p class="name">猪队友 <strong>主页</strong> </p>
          <p class="describe">与小猪杀入战场吧</p>
          <p class="text">"猪队友" 是一款多功能社交开黑平台。玩家可以在右上角个人中心包装自己。</p>
          <p class="text">添加个性标签，上线匹配开黑队友或直接多人开黑。点击小猪上线与好友一起享受开黑乐趣吧。</p>
        </div>
      </div>
    </div>
    <div class="page4">
      <div class="center">
        <p class="name">猪队友 <strong>陪玩</strong></p>
        <p class="describe">找陪玩或是当陪玩一切随心而变</p>
        <p class="text">一个人玩游戏是不是有些寂寞?<br>四缺一是不是有些无奈说不出?<br>找些志同道合的人一起开黑吧!</p>
      </div>
      <div class="carousel"></div>
    </div>
    <div class="page5">
      <div class="center">
        <div class="left">
          <p class="name">猪队友 <strong>认证</strong></p>
          <p class="describe">认证注册向大家展现幕布后精彩的你</p>
          <p class="text">妹子/大神在上传完资料后<br>我们会在第一时间由后台人工审核。<br>审核成功后会有独特的认证标志<br>并且可以成为陪玩自由定价开始接单啦。</p>
        </div>
        <img src="./assets/diwuping.png">
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'app',
  components: {
    // Hello
  }
}
</script>

<style lang = "less">
#app {
  min-width: 1300px;
  font-family:Arial,Helvetica;
  .page1{
    height: 700px;
    border:1px solid black;
    background: url("./assets/beijing.png") no-repeat ;
    background-size:cover;
    margin-bottom: 180px;
    .top{
      color: white;
      font-style: normal;
      img{
        display: inline-block;
        margin-left: 200px;
        vertical-align:-16px;
      }
      .text{
        display: inline-block;
        p{
          margin-top: 18px;
          margin-bottom: 2px;
          font-size: 26px;
          background: url("./assets/dingbuxian.png") no-repeat 0 29px;
        }
        span{
          font-size: 16px;
        }
      }
    }
    .context{
      img.left{
        width: 365px;
        margin-left: 244px;
        margin-top: 126px;
        vertical-align:-256px;
      }
      .right{
        width: 648px;
        margin-left: 145px;
        display: inline-block;
        img{
          margin-left: 32px;
        }
        p{
          width: 612px;
          height: 154px;
          font-size: 20px;
          color: white;
          line-height: 34px;
          border-bottom: 2px solid white;
          padding: 50px 20px 20px 20px;
          margin-top: -37px;
          background: url("./assets/xiankuang.png") no-repeat;
          background-size: cover;
        }
        .btn{
          display: inline-block;
          width: 180px;
          height: 62px;
          border-radius: 50px;
          line-height: 62px;
          text-align: right;
          padding-right: 25px;
          background-color: rgba(255, 255, 255, 0.5);
          font-size: 16px;
          color: white;
          border: 1px solid rgba(255, 255, 255, 0);
          margin-top: 58px;
        }
        
        .btn.iphone{
          background: url("./assets/apple.png") no-repeat;
          background-position: 27px 11px;
          background-color: rgba(255, 255, 255, 0.5);
          margin-left: 78px;
          /*span{
            width: 164px;
            height: 176px;
            display: inline-block;
          }*/
        }
        .btn.androd{
          background: url("./assets/android.png") no-repeat;
          background-position: 27px 11px;
          background-color: rgba(255, 255, 255, 0.5);
          margin-left: 88px;
        }
        .btn:hover{
          border: 1px solid rgba(255, 255, 255, 1);
          background-color: #ffda26;
        }
      }
    }
  }
  .page2{
    height:520px;
    .center{
      width: 965px;
      margin: 0 auto;
    }
    .left{
      width: 380px;
      height: 100%;
      display: inline-block;
      /*border: 1px solid black;*/
      img{
        width: 100%;
        margin: 0 auto;
        vertical-align:-130px;
      }
    }
    .right{
      width: 432px;
      margin-left: 144px;
      display: inline-block;
      /*border: 1px solid black;*/
      .name{
        font-size: 26px;
        color: #956adc;
        border-bottom: 1px solid #e7e7e7;
        width: 158px;
        margin: 0;
      }
      .describe{
        font-size: 20px;
        color: #353535;
        margin-top: 10px;
      }
      .text{
        font-size: 16px;
        color: #6d6d6d;
      }
    }
  }
  .page3{
    height: 753px;
    /*border:1px solid black;*/
    background: url("./assets/disanping-sanjiao.png") no-repeat 30px 0px;
    background-size: 1264px;
    .center{
      width: 1004px;
      height: 410px;
      background-color: white;
      padding-left: 156px;
      /*border:1px solid black;*/
      margin: 0 auto;
      margin-top: 115px;
      -moz-box-shadow:0px 2px 17px rgba(221, 196, 242, 0.5); 
      -webkit-box-shadow:0px 2px 17px rgba(221, 196, 242, 0.5); 
      box-shadow:0px 2px 17px rgba(221, 196, 242, 0.5);
      img{
        width: 270px;
        margin-top: -88px;
        vertical-align:-110px;
      }
      .right{
        width: 432px;
        margin-left: 144px;
        display: inline-block;
        /*border: 1px solid black;*/
        .name{
          font-size: 26px;
          color: #956adc;
          border-bottom: 1px solid #e7e7e7;
          width: 158px;
          margin: 0;
        }
        .describe{
          font-size: 20px;
          color: #353535;
          margin-top: 10px;
        }
        .text{
          font-size: 16px;
          color: #6d6d6d;
        }
      }
    }
  }
  .page4{
    height: 760px;
    border:1px solid black;
    .center{
      text-align: center;
      width: 283px;
      margin: 0 auto;
      .name{
        font-size: 26px;
        color: #956adc;
        border-bottom: 1px solid #e7e7e7;
        width: 212px;
        margin: 0 auto;
        margin-top: 50px;
        text-align: center;
      }
      .describe{
        font-size: 20px;
        color: #353535;
        margin-top: 10px;
      }
      .text{
        font-size: 16px;
        color: #6d6d6d;
      }
    }
    .carousel{
      border:1px solid black;
      width: 666px;
      height: 480px;
      margin: 0 auto;
    }
  }
  .page5{
    height: 770px;
    border:1px solid black;
    .center{
      text-align: center;
      width: 1070px;
      /*height: 344px;*/
      /*border:2px solid red;*/
      margin: 0 auto;
      margin-top: 126px;
      .left{
        width: 630px;
        height: 340px;
        border:10px solid #cacaca;
        border-right: none;
        background-color: #9668df;
        display: inline-block;
        /*padding-top: 55px;*/
        .name{
          font-size: 26px;
          color: white;
          border-bottom: 1px solid #e7e7e7;
          width: 158px;
          margin: 0 auto;
          margin-top: 55px;
        }
        .describe{
          font-size: 20px;
          color: white;
          margin-top: 10px;
        }
        .text{
          font-size: 16px;
          color: white;
          line-height: 30px;
        }
      }
      img{
        display: inline-block;
        width: 446px;
        margin-left: -21px;
        vertical-align: -155px;
      }
    }

  }

}
</style>
