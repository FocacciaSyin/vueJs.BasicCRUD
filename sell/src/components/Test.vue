<template>
  <div class="test">
    我是測試組件
    {{ msg }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "Woody made.",
    };
  },
};
</script>

<style>
.test {
  color: red;
}
</style>
