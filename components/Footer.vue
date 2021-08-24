<template>
  <section id="Footer">
    <div class="mobile-only">
      <div class="footer-nav">
        <ul class="footer-nav__menu">
          <li>HOME</li>
          <li>WORK</li>
          <li>ABOUT ME</li>
          <li>CONTACT ME</li>
        </ul>
        <ul class="footer-nav__contact">
          <li>aguilarmiqueas@gmail.com</li>
          <li>+54 0 362 4615433</li>
        </ul>
      </div>
      <div class="footer-links">
        <p>TWITTER / INSTAGRAM / LINKEDIN / GITHUB</p>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
  #Footer {
    background-color: #ffffff;
    color: #131313;
    padding: 16vw 12vw;
  }

  .footer-nav {
    padding-top: 10vw;
    margin-bottom: 30vw;

    .footer-nav__menu li {
      font-family: "Bebas Neue", sans-serif;
      font-size: 18vw;
      margin: 3.5vw 0;
      letter-spacing: -1px;
    } 
  }

  .footer-nav__contact li {
    font-family: "Bebas Neue", sans-serif;
    font-size: 7vw;
    letter-spacing: -1px;
    margin: 2vw 0;
  }

  .footer-links {
    p {
      font-family: "Bebas Neue", sans-serif;
      font-size: 5.75vw;
      text-align: center;
    }
  }
</style>