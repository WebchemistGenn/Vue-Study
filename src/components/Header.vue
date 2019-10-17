<template>
  <header>
    <h1>HEADER</h1>
  </header>
</template>

<style lang="scss" scoped>
$width: 1000px;
$color: red;

header {
  position: fixed;
  display: flex;
  top: 0;
  left: 0;
  align-items: center;
  width: 100%;
  height: 50px;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.2);

  h1 {
    color: $color;
    text-shadow: 0 0 12px $color;
  }
}
</style>
