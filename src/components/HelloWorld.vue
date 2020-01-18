<template>
  <div>
    <Row type="flex" justify="center" align="middle" class-name="row a2">
      <Col span="6">col-12</Col>
      <Col span="6">col-12</Col>
      <Col span="6">col-12</Col>
      <Col span="6">col-12</Col>
    </Row>
    <Row type="flex" justify="center" align="middle" class-name="row a2">
      <Col span="6">col-12</Col>
      <Col span="6">col-12</Col>
      <Col span="6">col-12</Col>
      <Col span="6">col-12</Col>
    </Row>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.a1{
  height: 100px;
  border-bottom: solid 1px  #ffffff;
  text-align: center;
}
.a2{
    background-color: black;
    height: 50px;
  }
</style>
