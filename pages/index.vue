<template>
  <div>
    <Navbar></Navbar>
    <Home></Home>
    <Works></Works>
    <About></About>
    <Footer></Footer>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Inter:wght@300&display=swap');

// CSS Reset
a,abbr,acronym,address,applet,article,aside,audio,b,big,blockquote,body,canvas,caption,center,cite,code,dd,del,details,dfn,div,dl,dt,em,embed,fieldset,figcaption,figure,footer,form,h1,h2,h3,h4,h5,h6,header,hgroup,html,i,iframe,img,ins,kbd,label,legend,li,mark,menu,nav,object,ol,output,p,pre,q,ruby,s,samp,section,small,span,strike,strong,sub,summary,sup,table,tbody,td,tfoot,th,thead,time,tr,tt,u,ul,var,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline}article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}body{line-height:1}ol,ul{list-style:none}blockquote,q{quotes:none}blockquote:after,blockquote:before,q:after,q:before{content:"";content:none}table{border-collapse:collapse;border-spacing:0}
$miki-black: #131313;
// 

html {
  font-size: 10px;
}

body {
  // background-color: #131313;
}

.title {
  font-family: "Bebas Neue", sans-serif;
  line-height: 0.85;
  font-size: clamp(1rem, 18vw, 16rem);
  letter-spacing: -1px;
}

.call-to-action {
  font-family: "Inter", sans-serif;
  font-size: 5vw;
  display: flex;
  align-items: center;
}

.call-to-action__text {
  margin: 0 3vw;
}

.call-to-action__line {
  height: 1px;
  width: 20px;
  background-color: white;
}
</style>