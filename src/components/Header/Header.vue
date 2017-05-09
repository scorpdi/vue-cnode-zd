<template>
  <div class="header">
    <div class="title">
      <i class="icon-menu"></i>
      <h1>CNODE社区</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {

    }
  },
  methods: {
    a ( ) {
      alert('1')
    }
  }
}
</script>

<style lang="scss">

  .header{
    position: relative;
    height:70px;
    background: #2196f3;
    i{
      position: absolute;
      z-index: 1;
      display: inline-block;
      -webkit-box-flex: 1;
      -ms-flex: 1;
      flex: 1;
      width: 25px;
      height: 25px;
    }
    i.icon-menu{
      left: 20px;
      top: 25px;
      background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/P…U3MTQgMCAwIDAgMFoiIHAtaWQ9IjE4NTAiIGZpbGw9IiNmZmZmZmYiPjwvcGF0aD48L3N2Zz4=) no-repeat;
      background-size: contain;
    }
    h1{
      color: #fff;
      font-weight: bold;
      -webkit-box-flex: 5;
      flex: 5;
    }
  }
</style>


