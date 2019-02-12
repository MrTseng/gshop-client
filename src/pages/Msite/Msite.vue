<template>
  <HeaderTop title="昌平区北七家宏福科技园(337省道北)">
    <span class="header_search" slot="left">
      <i class="iconfont icon-sousuo"></i>
    </span>
    <span class="header_login" slot="right">
      <span class="header_login_text">登录|注册</span>
    </span>
  </HeaderTop>
</template>

<script>
//组件的使用步骤1，引入组件路径
import HeaderTop from '../../components/HeaderTop/HeaderTop.vue';
//组件的使用步骤2，映射成标签
export default {
    components: {
        HeaderTop
    }
};
</script>

<style lang="stylus" rel="stylesheet/stylus">
</style>
