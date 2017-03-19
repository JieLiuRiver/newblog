<template>
    <div class="header-wrapper">
      <div class="inner f-clearfix">
        <!-- logo -->
        <div class="logo f-ib f-fl">
            <i class="line top"></i>
            <span class="title">EZLippi-浮生志</span>
            <i class="line bottom"></i>
        </div>

        <!-- 导航 -->
        <div class="f-ib nav-wrapper f-fr">
          <v-nav></v-nav>
        </div>

      </div>
    </div>
</template>
<script>
  import vNav from 'components/Navlist/Navlist'

  export default{
    name: 'header',
    props: {},
    data() {
      return {
      }
    },
    method: {

    },
    components: {
      vNav
    }
  };
</script>
<style scoped lang="stylus" rel="stylesheet/stylus">
  @import '../../common/css/computed.styl';

  .header-wrapper
    background-color: #f5f5f5
    .inner
      padding: 25px 0 20px
      width: 720px
      margin: 0 auto
      .logo
        .title
          font-size: 22px
          font-weight: bolder
          font-family: 'Neucha', "PingFang SC", "Microsoft YaHei", sans-serif
          line-height: 36px
        .line
          height: 2px
          background-color: #222
          width: 80%
          margin: 0 auto
          display: block
        .nav-wrapper
          width: 80%

</style>
