<template>
  <div class="header titleBg">
     <div class="logo"><img src="../assets/images/logo.png"></div>
     <div class="menu">
       <a href="javascript:void(0)" class="current">现货</a>
       <a href="javascript:void(0)">保证金</a>
       <a href="javascript:void(0)">永续合约</a>
       <a href="javascript:void(0)">市场</a>
       <a href="javascript:void(0)">账户</a>
       <a href="javascript:void(0)">更多<span class="iconfont arrow_down">&#xe627;</span></a>
     </div>
     <div class="top_right">
        <div class="language">简体中文 <span class="iconfont arrow_down">&#xe627;</span></div>
        <div class="notice"><span class="iconfont">&#xe626;</span></div>
        <div class="wallet">
          <span class="iconfont wallet_icon">&#xe625;</span>
          链接钱包
          <span class="iconfont arrow_right">&#xe627;</span>
        </div>
     </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped lang="less">

</style>