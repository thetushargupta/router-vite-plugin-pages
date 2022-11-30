<script setup lang="ts">
var map = new maplibregl.Map({
  container: "map",
  style: "https://demotiles.maplibre.org/style.json", // stylesheet location
  center: [-74.5, 40], // starting position [lng, lat]
  zoom: 9, // starting zoom
});
</script>

<template>
  <div id="map" style="width: 400px; height: 300px"></div>
</template>

<style scoped></style>
