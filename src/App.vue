<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
   <h1>LOGO</h1>
      <nav>
        <ul>
          <li><a href="#">HOME</a></li>
          <li><a href="pages/about.html">ABOUT</a></li>
          <li><a href="pages/contact.html">CONTACT</a></li>
          <li><a href="pages/profil.html">PROFIL</a></li>
        </ul>
      </nav>
 
    <div id="mainContainer">
      <main>MAIN</main>
      <aside>ASIDE</aside>
    </div>

       
   
      <h2>FOOTER</h2>
</template>



<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

body,h1,ul{
    margin : 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
}
h2,h1{
    background-color: #f1f1f1;
    width:100%;
    margin : 0;
    text-align: center;
    padding: 50px 0 ;
}

h1,nav{
    padding: 50px;
}

ul{
   list-style: none;
   display: flex;
   justify-content: space-between;
   flex-wrap: wrap;
}

#mainContainer{
    display: flex;
    flex-wrap: wrap;
}
main,aside{
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
}

main{
    background-color:#aaa;
    width: 70%;
}
aside{
    background-color:#ccc;
    width: 30%;
}

@media screen and ( max-width:768px){
    main,aside{
        width: 100%;
    }
}
</style>
