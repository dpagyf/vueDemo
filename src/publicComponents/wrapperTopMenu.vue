<template>

    <Header class="headerBcolor">
      <Menu class="headerBcolor" mode="horizontal"  active-name="1">
        <div class="layout-logo"></div>
        <div class="layout-nav">
          <MenuItem name="1">
            <Icon type="ios-navigate"></Icon>
            Item 1
          </MenuItem>
          <MenuItem name="2">
            <Icon type="ios-keypad"></Icon>
            Item 2
          </MenuItem>
          <MenuItem name="3">
            <Icon type="ios-analytics"></Icon>
            Item 3
          </MenuItem>
          <MenuItem name="4">
            <Icon type="ios-paper"></Icon>
            Item 4
          </MenuItem>
        </div>
      </Menu>
    </Header>

</template>

<script>


  export default {

  }
</script>

<style scoped>
  .headerBcolor{background-color:#2B333C}
  .layout-logo{
    width: 100px;
    height: 30px;
    background: #5b6270;
    border-radius: 3px;
    float: left;
    position: relative;
    top: 15px;
    left: 20px;
  }
  .layout-nav{
    width: 420px;
    margin: 0 auto;
    margin-right: 20px;
  }
  .fullHeight{
    height: 100%;
  }

  .ivu-menu-horizontal.ivu-menu-light:after{background: #2B333C;}
</style>
