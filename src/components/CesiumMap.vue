<template>
    <div id="cesiumContainer"></div>
</template>

<script>


export default {
    name: 'CesiumMap',
    mounted() {
        let Cesium = window.cesium;
        Cesium.Ion.defaultAccessToken = '[YOUR_CESIUM_TOKEN]';
        var viewer = new Cesium.Viewer('cesiumContainer');
    }
}
</script>

<style scoped>
.viewer {
  width: 100%;
  height: 400px;
}
<style>