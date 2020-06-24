<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
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

/* 
Guia de estilos 

------section------
titulos: 
font-family: Open Sans
font-size: 40px

subtitulos:
font-family: Open Sans
font-size: 25px

-----body--------
titulos: 
font-family: Lato
font-size: 25px 

subtitulos: 
font-family: Lato
font-size: 14px

-----titulos-------
h1: extra-bold (800)
h2: bold (700)
h3: regular (400)
h4: lato 

---paleta de colores-----
nickel: #707070
rich black: #000f08
ginder: #b36b01
sweet brown: #a4452c

----definir------
h1:
p:
li:
ul: 
links: 

*/

</style>
