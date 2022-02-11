<template>
  <header>
      <figure>
       <img src="@/assets/img/dc-logo.png" alt="logo">
     </figure>
     <nav>
       <ul>
         <li v-for= '(option, index) in options' :key='index'>
           <a :href="option.url" :class="{active: option.active}">
             {{ text }}</a></li>
       </ul>
     </nav>
  </header>
</template>

<script>
export default {
name: "Header",
data() {
  return {
    options: [ 
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
      { text: "Characters", url: "#", active: false },
    ], 
  };
},
};

</script>

<style scoped>

header {
    height: 150px;
    background-color: white;
    display: flex;
    justify-content: space-around;
    
}

figure {
    padding-top: 1%;
}

ul {
    display: flex;
    justify-content: space-around;
    list-style: none;
   
}

li {
    color: white;
    vertical-align: middle;
     margin: 60px 10px;
}
</style>