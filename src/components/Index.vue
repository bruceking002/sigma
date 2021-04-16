<template>
  <div class="main">

    <TradeMenu/><!--指数-->
    <div class="content">
       <LeftBar/>
       <div class="rightbar">右边</div>
    </div>
    
  </div>
</template>

<script>
import TradeMenu from './TradeMenu'
import LeftBar from './LeftBar'

export default {
  name: "Index",
  data() {
    return {
      msg: "",
    };
  },
  components:{
    TradeMenu,
    LeftBar,
  }
};
</script>


<style scoped lang="less">
.content{
  display: flex;
  position: relative;
  height: calc(100% - 86px);
  overflow: hidden;
}
</style>