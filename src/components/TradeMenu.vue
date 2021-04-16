<template>
  <div class="tradeMenu titleBg">
    <div class="select_trade">
      <div class="coin_img"><img src="../assets/images/btc.png" /></div>
      <div class="coin_name">
        BTC/USDT永续合约
        <span class="greenColor">$60001.18</span>
      </div>
      <div class="arrow_down"><span class="iconfont">&#xe627;</span></div>
    </div><!--select_trade end-->

    <div class="trade_data">
       <div class="item">指数<span class="whiteColor">$59998.69</span></div>
       <div class="item">预言机<span class="whiteColor">$59998.69</span></div>
       <div class="item">24H涨跌<span class="greenColor">+0.25%</span></div>
       <div class="item">未平仓合约<span class="whiteColor">$59998.69</span></div>
       <div class="item">1H资金<span class="whiteColor">$59998.69</span></div>
       <div class="item">24H交易量<span class="whiteColor">$59998.69</span></div>
       <div class="item">24H交易额<span class="whiteColor">$59998.69</span></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TradeMenu",
  data() {
    return {
      msg: "",
    };
  },
};
</script>


<style scoped scoped lang="less">
.tradeMenu {
  margin-bottom: 10px;
  min-height: 76px;
  max-height: 76px;
  border-radius: 6px;
  display: flex;
  align-items: center;
  .select_trade {
    display: flex;
    align-items: center;
    padding-right: 35px;
    border-right: 1px solid #4E566E;
    .coin_img {
      margin-left: 26px;
      img {
        width: 40px;
        height: 40px;
      }
    }
    .coin_name {
      margin-left: 30px;
      span {
        display: block;
        margin-top: 5px;
        font-size: 24px;
        font-weight: 500;
      }
    }
    .arrow_down{
      margin-left: 15px;
      span{
        font-size: 12px;
      }
    }
  }

  .trade_data{
    display: flex;
    align-items: center;
    .item{
      margin-left: 48px;
      span{
        display: block;
        font-size: 18px;
        font-weight: 500;
        margin-top: 8px;
      }
    }
  }

}
</style>
