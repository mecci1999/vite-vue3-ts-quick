<script lang="ts">
import { defineComponent } from "vue";
import { ElButton } from "element-plus";

export default defineComponent({
  setup() {
    return {
      name: "I am Mecci",
    };
  },

  components: {
    ElButton,
  },
});
</script>

<template>
  <div class="div0">
    <div class="div1">hello,world!</div>
    <el-button>{{ name }}</el-button>
  </div>
</template>

<style lang="scss" scoped>
@import "./styles/normalize.scss";
@import "./styles/global.scss";
</style>
