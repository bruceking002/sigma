<template>
  <div class="leftbar">
     <div class="account titleBg">
        <div class="account_title">账户</div>
        <ul>
            <li><span>1888.00$</span>净值</li>
            <li><span>888.00$</span>净值</li>
            <li><span>1888.00$</span>50%</li>
            <li><span>1888.00$</span>净值</li>
        </ul>
     </div>
  </div>
</template>

<script>
export default {
  name: 'LeftBar',
  data () {
    return {
      msg: ''
    }
  }
}
</script>


<style scoped lang="less">
@import url('~@/assets/css/leftbar.less');
</style>