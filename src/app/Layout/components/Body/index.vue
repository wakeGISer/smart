<template>
  <div class="main-container">
    <div id="map"></div>
    <LeftBar ref="leftbar"></LeftBar>
    <RightBar ref="rightbar"></RightBar>
    <BottomBar ref="bottombar"></BottomBar>
  </div>
</template>

<script>
  import LeftBar from './components/LeaftBar'
  import RightBar from './components/RightBar'
  import BottomBar from './components/BottomBar'
  export default {
    name: 'mapcontainer',
    components: {
      LeftBar,
      RightBar,
      BottomBar
    }
  }
</script>
