<template>
  <header>
    <div class="nav">
      <ul class="nav-List">
        <li>
          <a href="#">健康保健</a>
        </li>
        <li>
          <a href="#">健康服务</a>
        </li>
        <li>
          <a href="#">健康服务</a>
        </li>
        <li>
          <a href="#">
            <img src="" alt="易联众">
          </a>
        </li>
        <li>
          <a href="#">理赔服务</a>
        </li>
        <li>
          <a href="#">资讯中心</a>
        </li>
        <li>
          <a href="#">注册/登录</a>
        </li>
      </ul>
    </div>
    <div class="nav-floatLiast">
      <ul>
        <li>
          <a href="">
            <i class="icon iconfont icon-yiwaishanghai"></i>
            <div class="name">意外伤害</div>
          </a>
        </li>
        <li>
          <a href="">
            <i class="icon iconfont icon-yiliaobaoxian"></i>
            <div class="name">医疗保险</div>
          </a>
        </li>
        <li>
          <a href="">
            <i class="icon iconfont icon-renshoubaoxian"></i>
            <div class="name">人寿保险</div>
          </a>
        </li>
        <li>
          <a href="">
            <i class="icon iconfont icon-shinengshourusunshi"></i>
            <div class="name">失能收入损失</div>
          </a>
        </li>
        <li>
          <a href="">
            <i class="icon iconfont icon-hulibaoxian"></i>
            <div class="name">护理保险</div>
          </a>
        </li>
        <li>
          <a href="">
            <i class="icon iconfont icon-jibingbaoxian"></i>
            <div class="name">疾病保险</div>
          </a>
        </li>
        <li>
          <a href="">
            <i class="icon iconfont icon-jiankangguanli"></i>
            <div class="name">健康管理</div>
          </a>
        </li>
      </ul>
    </div>
  </header>
</template>

<script type="text/ecmascript-6">
  require('assets/iconfont.css')
  export default {}
</script>

<style lang="scss" rel="stylesheat/sass">
  @mixin menuaction($color) {
    background: linear-gradient($color 100%, transparent 100%) no-repeat center top/92px 6px;
  }

  body{
    background-color: #fafafa;
  }
  header{
    width: 1080px;
    margin: auto;
    padding-left: 25px;
  }
  .nav{
    font-size: 36px;
    width: 1080px;
    height: 200px;
    margin-bottom: 30px;
    .nav-List{
      li{
        width: 154px;
        float: left;
        font-size: 21px;
        text-align: center;
        padding-top: 88px;
        &:hover{
          @include menuaction(#3da1ff);
          cursor: pointer;
          a{
            color: #3da1ff;
          }
        }
      }
    }
  }
  .nav-floatLiast{
    width: 1080px;
    display: none;
    ul{
      li{
        width: 154px;
        float: left;
        font-size: 17px;
        text-align: center;
        i{
          font-size: 62px;
          color: #3da1ff;
        }
      }
    }
  }
</style>
