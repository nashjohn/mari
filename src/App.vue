<template>
  <menu>
    <div class="logo"><img src="imgs/logo.png"/></div>
  </menu>
  
  <section class="stsection">
    <h1 class="title">Maricanna</h1>
    <p class="title-text">Regenerative Farming Inputs</p>
  </section>
  <footer>
    <div class="socials"> 
      <a href="https://www.instagram.com/maricannausa/" target="_blank"><svg class="instagram" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><!--! Font Awesome Pro 6.0.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"/></svg></a>
    </div>
    <p class="copytright">&copy; 2020 Maricanna</p>

  </footer>
</template>

<script>

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.stsection {
  height: 100vh;
  background-image: url(assets/greenhouse.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
menu {
  margin: 0;
  padding: 0;
  display: block;
  height: 50px;
  width: auto;
}
.instagram {
  height: 2.5vh;
  width: auto;
}
.logo {
}
@font-face {
  font-family: Americanna;
  src: url(assets/fonts/BALLW___.TTF);
}
h1 {
  font-family: Americanna;
  font-size: 600%;
  margin-top: 0;
  padding-top: 0;
}
.title {
  color: #AED3F2;
  display: none;
}
.title-text {
  color: #EBF1F2;
  display: none;
}
footer {
  padding-top: .5em;
}
.socials {
  display: flex;
  flex-direction: row-reverse;
  width: 100%;
}
.copytright {
  font-size: .75em;
}
</style>
