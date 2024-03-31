<template>
  <div class="container">
    <div class="left-board">
      <div class="top">
        <img :src="logo" alt="" />Form Generator
        <a
          class="github"
          href="https://github.com/pzzyf/vue2-form-generator"
          target="_blank"
        >
          <img src="https://github.githubassets.com/pinned-octocat.svg" alt />
        </a>
      </div>
      <el-input></el-input>
    </div>
    <div class="center-board">2</div>
    <div class="right-board">3</div>
  </div>
</template>

<script>
import logo from "@/assets/logo.png";
export default {
  data() {
    return {
      logo,
    };
  },
};
</script>

<style lang="scss" scoped>
@import "@/styles/home";
</style>
