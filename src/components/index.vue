<template>
  <div class="index">
    <Header></Header>
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './header/header'
import Footer from './footer/footer'

export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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
@color:#666;
h1{
  color: @color;
}
h2{
  color: @commoncolor;
}
</style>
