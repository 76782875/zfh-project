<template>
  <div class="wrapper">
    <Header></Header>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './header/header'
import Footer from './footer/footer'

export default {
  data () {
    return {
    }
  },
  components:{
    Header,
    Footer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less">
@import '../../static/less.less';
.wrapper{
  width: 100%;
  min-width: 1200px;
}

</style>
