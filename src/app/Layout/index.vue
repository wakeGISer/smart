<template>
  <div class="layout">
    <NavBar ref="navbar"></NavBar>
    <MapContainer ref="mapcontainer"></MapContainer>
  </div>
</template>

<script>
  import NavBar from './components/Header'
  import MapContainer from './components/Body'
  export default {
    name: 'layout',
    components: {
      NavBar,
      MapContainer
    }
  }
</script>

<style scoped src="./theme/style/index.css"></style>
<style src="./theme/style/component.css"></style>
<style src="./theme/style/case.css"></style>
<style src="./theme/style/normalize.css"></style>
<style src="./theme/style/custom.css"></style>
<style src="./theme/style/main.css"></style>
