<template>
  <div>
  <Header/>
  <Main/>
  
  <Footer/>
  
  
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Footer from "./components/Footer.vue"


export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
    
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  max-width: 100vh;
  height: auto;
}

a {
  color: dodgerblue;
  text-decoration: none;
}

body {
  min-height: 100vh;
  font-family: sans-serif;
}

/* Utilities */

.container {
  margin: 0 auto;
  max-width: 1200px;
}

.clickable {
  cursor: pointer;
}

.h-100 {
  height: 100%;
}

</style>
