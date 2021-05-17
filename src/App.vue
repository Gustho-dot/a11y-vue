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

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
