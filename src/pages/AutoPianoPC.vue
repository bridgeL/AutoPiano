<style lang="less">
@import url("../assets/style/variable.less");
.page-pc {
  width: 100%;
  min-width: 1280px;
  height: 100%;
  padding: 1px;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  position: absolute;
  top: 0;
  left: 0;
  overflow-x: scroll;
  .app-content {
    width: 100%;
    height: 100%;
    overflow-y: scroll;
    position: relative;
    .piano-scroll-wrap {
      overflow: hidden;
    }
  }
}
</style>

<template>
  <div class="page-pc">
    <div class="app-content">
      <Piano></Piano>
    </div>
  </div>
</template>

<script>
import Piano from "@/components/Piano";

export default {
  name: "AutoPianoPC",
  components: {
    Piano,
  },
};
</script>
