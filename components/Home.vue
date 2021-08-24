<template>
  <section id="Home">
    <div class="title-wrap">
      <h1 class="title">MIQUEAS <br>ARISMENDI <br></h1>
      <h1 class="subtitle title">WEB DEVELOPER</h1>
    </div>
    <div class="call-to-action">
      <div class="call-to-action__line"></div>
      <div class="call-to-action__text">SEE MY WORK</div>
      <div class="call-to-action__line"></div>
    </div>
  </section>
</template>

<script>
export default {
  
}
</script>

<style lang="scss" scoped>
#Home {
  background-color: #131313;
  color: #FFFFFF;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  position: relative;

  width: 100%;
  min-height: 100vh;
  
}
.subtitle.title {
  font-size: clamp(1rem, 12.5vw, 11rem);
  margin-top: 1vw;
}
.title-wrap {
  margin-top: 20rem;
  text-align: center;
}

.call-to-action {
  position: absolute;
  bottom: 6rem;
}
</style>