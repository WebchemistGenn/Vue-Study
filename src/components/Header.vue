<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: "Header"
    }
  }
};
</script>

<style lang="scss" scoped>
$width: 1000px;

header {
  position: fixed;
  display: flex;
  top: 0;
  left: 0;
  align-items: center;
  width: 100%;
  height: 50px;
  padding: 0 20px;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.2);

  h1 {
    font-size: 18px;
  }
}
</style>
