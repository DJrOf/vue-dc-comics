<template>
  <header>
      <figure>
       <img src="@/assets/img/dc-logo.png" alt="logo">
     </figure>
     <nav>
       <ul>
         <li><a href="">Characters</a></li>
         <li><a href="">Comics</a></li>
         <li><a href="">Movies</a></li>
         <li><a href="">TV</a></li>
         <li><a href="">Games</a></li>
         <li><a href="">Collectibles</a></li>
         <li><a href="">Videos</a></li>
         <li><a href="">Fans</a></li>
         <li><a href="">News</a></li>
         <li><a href="">Shop</a></li>
       </ul>
     </nav>
  </header>
</template>

<script>
export default {
name: "Header",
}
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