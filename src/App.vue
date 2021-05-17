<template>
  <div id="app">
     <section class="nav-section"> 
       <img class="logo" src="./assets/images/logo.png" alt="logo" />
       <nav class="nav">
         <ul>
           <li>
             <router-link to="/">Home</router-link> 
           </li>
           <li>
             <router-link to="/about">About</router-link> 
           </li>
           <li>
            <router-link to="/contact">Contact</router-link>
           </li>
         </ul>
       </nav>
       </section>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#app {
  width: 80vw;
  margin: 0 auto;
}
 .nav-section {
 background-color: aquamarine;
 display: flex;
 justify-content: space-between;
 align-items: center;
}
.logo {
 height: 10em;
 width: 10em;
 margin-left: 1em;
}
.nav {
margin-right: 5em;
}
.footer {
 background-color: aquamarine;
 height: 15em;
 width: 100%;
 display: flex;
 justify-content: space-between;
 align-items: center;
}
.socialMedia, .info {
padding: 3em;
text-align: center;
padding-top: 0;
}
.mediaImage {
width: 5em;
height: 5em;
}
h5, h6 {
 font-size: 1.2em;
}
</style>
