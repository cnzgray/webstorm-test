<template>
  <div>
    <!-- FIXME: don's parse ComponentA -->
    <component-a :value="test"></component-a>

    <el-input label="input1"></el-input>
  </div>
</template>

<script>
import { ComponentA } from "@test/components";
import { ElInput } from "element-ui";

export default {
  name: "App",
  components: { ComponentA, ElInput }
};
</script>
