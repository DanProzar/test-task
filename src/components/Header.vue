<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="col-md-2">
          <img src="../assets/logo.png" alt="">
        </div>
        <div class="col-md-7">
          <Menu />
        </div>
        <div class="col-md-3">
          <Account />
        </div>
      </div>
    </div>
  </header>
</template>
<script>
import Menu from '../components/Menu'
import Account from '../components/Account'
export default {
  name: 'header',
  components: {
    Menu,
    Account
  }
}
</script>
<style lang="scss" scoped>
  header {
    position: fixed;
    top: 0;
    right: 0;
    left: 0;
    background-color: #fff;
    -webkit-box-shadow: 0px 5px 15px -15px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px 5px 15px -15px rgba(0,0,0,0.75);
    box-shadow: 0px 5px 15px -15px rgba(0,0,0,0.75);
    z-index: 99;
    .row {
      align-items: center;
    }
  }
</style>