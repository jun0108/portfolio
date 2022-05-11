<template>
  <div>hi test</div>
</template>

<script>
import { reactive } from "@vue/composition-api";

export default {
  name: "index",
  components: {},
  setup() {
    const state = reactive({
      text: "testTitle",
    });

    return { state };
  },
};
</script>

<style lang="scss" scoped></style>
