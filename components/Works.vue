<template>
  <div id="Works">
    <h2 class="title">PROJECTS</h2>
    <article v-for="n in 4" class="project">
      <h3>Title</h3>
      <div class="project-block">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa illum architecto perferendis magnam error. Non voluptates modi atque suscipit? Molestias corrupti quod quam impedit. At corrupti autem a dolor iste.</p>
        <div class="call-to-action">
          <div class="call-to-action__line"></div>
          <div class="call-to-action__text">VIEW CASE STUDY</div>
          <div class="call-to-action__line"></div>
        </div>
      </div>
      <p class="project-text mobile-only">Lorem ipsum dolor sit amet consectetur adipisicing elit. Id quod eveniet qui, sit odio voluptates et dolores cupiditate omnis corporis temporibus! Natus totam minus corporis?</p>
    </article>
  </div>
</template>

<style lang="scss" scoped>
#Works {
  background-color: #131313;
  color: #ffffff;
  padding: 16vw 12vw;
  margin: 0;
}

h2.title {
  font-size: clamp(1rem, 12.5vw, 11rem);
  margin-bottom: 20vw;
}

.project {
  margin-bottom: 16vw;
  h3 {
    font-family: "Bebas Neue", sans-serif;
    font-size: clamp(1rem, 10vw, 40rem);
  }
}

.project:last-of-type {
  margin-bottom: 4vw;
}

.project-block {
  background-color: white;
  width: 100%;
  height: 80vw;
  margin: 4vw 0;

  p {
    color: white;
    font-family: "Inter", sans-serif;
    display: none;
  }
}

.project-text {
  color: white;
  font-family: "Inter", sansa-serif;
  font-size: 5vw;
  line-height: 1.2;
}
</style>