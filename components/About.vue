<template>
  <section id="About">
    <div class="about-text">
      <h2>ABOUT ME</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex quia accusamus dolorem sapiente eligendi iste laudantium modi aliquid dicta cum culpa deleniti, et sint voluptatibus molestias suscipit blanditiis obcaecati praesentium.
      Possimus iusto non, quo explicabo illo, illum minus unde, quia vero dolorum nemo reprehenderit facilis voluptates et obcaecati aliquam rerum laudantium aut incidunt iste! Et iusto quisquam velit totam eligendi.
      Omnis minus soluta, quidem magnam minima doloribus consequuntur consequatur delectus atque ullam, tempore provident expedita et assumenda. Quae, possimus consectetur, quaerat veniam quos commodi eaque dolore, consequatur necessitatibus earum eius!
      Provident corporis corrupti sunt eius autem ad hic pariatur quasi repellendus doloribus dignissimos, accusamus alias impedit iste laboriosam voluptatum exercitationem temporibus illo odio quo mollitia quod nihil! Repellendus, quis quia.</p>
    </div>

    <div class="skills">
      <div class="skill">
        <h3>FRONT-END SKILLS</h3>
        <p>HTML / CSS / JAVASCRIPT / GSAP / REACT / VUE</p>
      </div>
      <div class="skill">
        <h3>BACK-END SKILLS</h3>
        <p>NODE / C# / .NET CORE</p>
      </div>
      <div class="skill">
        <h3>OTHER SKILLS</h3>
        <p>GIT / PHOTOSHOP / FIGMA / AGILE METHODOLOGIES</p>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
#About {
  background-color: #131313;
  color: #ffffff;
  padding: 16vw 12vw;
  padding-top: 0;
  font-family: "Bebas Neue", sans-serif;

  h2 {
    font-size: clamp(1rem, 12.5vw, 60rem);
    margin-bottom: 20vw;
  }

  h3 {
    font-size: clamp(1rem, 10vw, 60rem);
  }
  
  p {
    font-family: "Inter", sansa-serif;
    font-size: 5vw;
    line-height: 1.2;
  }
}

.about-text {
  margin-bottom: 18vw;
}

.skills {
  margin: 24vw 0 8vw;
  p {
    margin: 2vw 0;
  }
}

.skill {
  margin: 12vw 0;
}
</style>