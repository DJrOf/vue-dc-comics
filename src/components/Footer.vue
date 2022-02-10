<template>
  <footer>


<div class="footerlist" >
    <ul>
        <li><h1>asd</h1></li>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
    </ul>
    <ul>
        <li><h1>Shop</h1></li>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
    </ul>
</div>
<div class="footerlist" >
    <ul>
        <li><h1>DC</h1></li>
        <li>Terms of Use</li>
        <li>Privacy</li>
        <li>Ad</li>
        <li>Jobs</li>
        <li>Subscription</li>
        <li>Talent</li>
        <li>Ratings</li>
        <li>Shop</li>
        <li>Contacts</li>
    </ul>
</div>
<div class="footerlist" >
    <ul>
        <li><h1>Sites</h1></li>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC universe</li>
        <li>DC Power Vise</li>
    </ul>
</div>

<div class="footerlist" >
   <img src="@/assets/img/dc-logo-bg.png" alt="">
</div>
<!-- <div class="contacts">

</div> -->
  </footer>
</template>

<script>
export default {
name: "Footer",
}
</script>

<style scoped>

img {
    margin-left: 700px;
    height: 300px;
}

footer {
    height: 50.73vh;
    background-color: green;
    background-image: url("../assets/img/footer-bg.jpg"); 
    margin: 0;
    padding: 3%;
    display: flex;
}

.footerlist {
    padding: 1%;
    color: white;
}

ul {
    list-style: none;
    margin: 0;
}

h1 {
    margin-top: 10px;
}

li {
    margin: 0;
}

/* .contacts {
    height: 80px;
    background-color: darkgray;
    width: 100%;
   
} */

</style>