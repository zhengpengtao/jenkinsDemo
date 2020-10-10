<template>
  <div class="wrap">
    <div class="yy-btn">
      预约{{ msg }}
    </div>
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '12'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .wrap{
    width: 100%;
    height: 100vh;
    background: rgba(242,244,248,1);
  }
  .yy-btn{
    margin: 180px auto;
    display: inline-block;
    width: 150px;
    height: 150px;
    box-shadow:0 0 16px red;
    -moz-box-shadow:0 0 16px red;
    -webkit-box-shadow:0 0 16px red;
    font-size: 32px;
    text-align: center;
    line-height: 150px;
    font-weight: 600;
    color: #ffffff;
    border-radius: 100%;
    background: #788CFA;
  }
</style>
