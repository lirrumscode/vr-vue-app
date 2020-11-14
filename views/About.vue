<template>
  <a-scene>
    <a-sky
      src="https://e4youth.org/wp-content/uploads/2019/02/eifelcover-1320x564.jpg"
      rotation="0 -130 0"
    ></a-sky>
    <a-text
      font="kelsonsans"
      value="Made by Lirrums"
      width="8"
      position="-2.5 0.25 -1.5"
      rotation="0 15 0"
    ></a-text>
  </a-scene>
</template>
<script>
require("aframe");

export default {
  components: {},
};
</script>

<style lang="scss">
#container {
  width: 100%;
  height: 400px;
}
</style>
