<template>
  <div class="bigBox">
      <div class="header content-center">
          <div class="head-img"></div>
          <div class="logo"></div>
      </div>
      <div class="navBox content-center">
        <ul class="nav">
            <li>看帖</li>
            <li>图片</li>
            <li>精品</li>
            <li>视频</li>
            <li>群组</li>
        </ul>
      </div>
      <div class="tieZiList content-center">
          <div class="tiezi">
              <div class="tieziNum">
                  <span class="tieziNumSpan">123</span>
              </div>
              <div class="tieziContent">
                  <p class="tieziTitle">听说华为又要出新款机子了，你会去买单吗？</p>
              </div>
          </div>
          <div class="tiezi">
              <div class="tieziNum">
                  <span class="tieziNumSpan">123</span>
              </div>
              <div class="tieziContent">
                  <p class="tieziTitle">听说华为又要出新款机子了，你会去买单吗？</p>
              </div>
          </div>
          <div class="tiezi">
              <div class="tieziNum">
                  <span class="tieziNumSpan">123</span>
              </div>
              <div class="tieziContent">
                  <p class="tieziTitle">听说华为又要出新款机子了，你会去买单吗？</p>
              </div>
          </div>
          <div class="tiezi">
              <div class="tieziNum">
                  <span class="tieziNumSpan">123</span>
              </div>
              <div class="tieziContent">
                  <p class="tieziTitle">听说华为又要出新款机子了，你会去买单吗？</p>
              </div>
          </div>
          <div class="tiezi">
              <div class="tieziNum">
                  <span class="tieziNumSpan">123</span>
              </div>
              <div class="tieziContent">
                  <p class="tieziTitle">听说华为又要出新款机子了，你会去买单吗？</p>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style >
    *{
        list-style: none;
    }
    .tiezi{
        display: flex;
        padding-top: 15px;
        padding-bottom: 15px;
        /* border-top: 1px solid #000; */
        border-bottom: 1px solid #000;
    }
    .tieziNumSpan{
        display: inline-block;
        width: 54px;
        height: 24px;
        border: 1px solid black;
        border-radius: 3px;
        line-height: 24px;
        text-align: center;
        font-size: 12px;
        background: rgb(247,247,247);
    }
    .tieziNum{
        width: 95px;
        text-align: center;
    }
    .tieziContent{

    }
    .tieZiList{
        width: 960px;
        height: 960px;
        background: white;
    }
    .bigBox{
        width: 100%;
        background: rgb(220,239,254);
    }
    .content-center{
        position: relative;
        left: 0;
        right: 0;
        margin: 0 auto;
    }
    .header{
        width: 960px;
        height: 270px;
        background-color: green;
    }
    .head-img{
        width: 100%;
        height: 158px;
        background: blue;
    }
    .logo{
        width: 160px;
        height: 160px;
        position: absolute;
        left: 20px;
        bottom: 15px;
        background: red;
    }
    .nav{
        display: flex;
        border-bottom: 1px solid #000;
        
    }
    li{
            height: 45px;
            width: 76px;
            background-color: white;
            text-align: center;
            line-height: 45px;
            font-size: 15px;
        }
    .navBox{
        width: 960px;
    }
</style>