<template>
<div class="header">
    <div class="nav">
      <img src="../../assets/logo.png" alt="">
      <ul>
          <li><a>首页</a></li>
          <li><a>关于我们</a></li>
          <li><a>服务范围</a></li>
          <li><a>行业资讯</a></li>
          <li><a>执业资格</a></li>
          <li><a>文化党建</a></li>
          <li><a>经典客户</a></li>
          <li><a>福华爱心</a></li>
          <li><a>联系我们</a></li>          
      </ul>
  </div>
</div>
</template>

<script>
export default {
    name:'Header'
}
</script>

<style lang="less">
@import '../../../static/less.less';
@navbg: rgba(0,0,0,0.1);
@navcolor: #ffffff;
@navfont: 12px;
.header{
    width: 100%;
    background: @navbg;
    .nav{
        display: flex;
        width: 1200px;
        height: 80px;
        justify-content: space-between;
        align-items: center;
        margin: auto;
        color: #000000;
        img{
            width: 70px;
            height: 70px;
        }
        ul{
            display: flex;
            justify-content: flex-end;
            align-items: center;
            height: 80px;
            li{
                color: @navcolor;
                font-size: @navfont;
                padding-left: 20px;
            }
        }
    }
}

</style>

