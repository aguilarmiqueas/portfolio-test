<template>
  <div id="Navbar">
    <div class="line"></div>
    <div class="line"></div>
    <div class="line"></div>
  </div>
</template>

<style lang="scss" scoped>
#Navbar {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  position: fixed;
  top: 8vw;
  right: 8vw;
  z-index: 1;
}

.line {
  width: 28px;
  height: 2px;
  background-color: white;
  margin: 2.5px 0;
  z-index: 1;
}
</style>