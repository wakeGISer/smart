<template>
  <nav class="navbar navbar-glass navbar-fixed-top">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="http://portal.smartxspace.com/App/cityCase/cityCase.html#">
          <img alt="logo" src="./theme/img/cityCase.png">
          <div class="navbar-title">
            <span class="navbar-brand-text">城市事件</span>
            <span class="navbar-brand-subtext">City Cases</span>
          </div>
        </a>
      </div>
      <div class="navbar-header offSet">
        <a class="navbar-brand" href="http://portal.smartxspace.com/App/SmartCity/index.html">
          <!-- <img alt="logo" src="images/logo.png"> -->
          <div class="navbar-title">
            <span class="navbar-brand-text">智慧城市综合运营管理中心</span>
            <span class="navbar-brand-subtext">Smart City Center@立得空间</span>
          </div>
        </a>
      </div>
      <div class="navbar-collapse collapse">
        <ul class="nav navbar-nav navbar-left">
          <li class="date-line">
            <div class="navbar-title">
              <span class="navbar-brand-subtext" id="date">2017 06 05 星期一</span>
              <span class="navbar-brand-text" id="clock"><span style="float:left">09</span><span id="online" style="width:16px; display:block; float:left">: </span><span style="float:left">09</span><span id="online2" style="width:16px; display:block; float:left">: </span><span style="float:left">24</span></span>
            </div>
          </li>
        </ul>
        <ul class="nav navbar-nav navbar-right">
          <li><a href="http://portal.smartxspace.com/App/SmartCity/index.html"><span class="glyphicon glyphicon-home" aria-hidden="true"></span></a></li>
        </ul>
      </div>
    </div>
  </nav>

</template>
<script>
  export default {
    name: 'navbar'
  }
</script>

<style scoped src="./theme/style/index.css"></style>
