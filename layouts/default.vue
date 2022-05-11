<template>
  <div class="flex flex-col uvms">
    <div class="flex-1 content">
      <Nuxt />
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import VueCompositionApi from "@vue/composition-api";

Vue.use(VueCompositionApi);
export default {
  name: "Default",
  components: {},
  data() {
    return {};
  },
};
</script>

<style lang="scss">
// 레이아웃
.uvms {
  height: 100vh;
  margin: 0 auto;
  .content {
    overflow-y: auto;
    height: calc(100vh - 50px);
    padding: 30px 20px 20px;
  }
}
</style>
