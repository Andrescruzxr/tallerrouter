<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |||----
      <router-link to="/about">About</router-link>|---
      <router-link to="/Inicio">Inicio</router-link>|---
      <router-link to="/dashboard.Admin">dashboard.admin</router-link>|---
       <router-link to="/create">Create</router-link>|---
        <router-link to="/update">Update</router-link>|--
        <router-link to="/index">Inicio</router-link>|---
        <router-link to="/dashboard.usuario">Dashboard.usuario</router-link>|--
        <router-link to="/Rol">ROL</router-link>|---
        <router-link to="/Inicio.sesion">iNICIO SESION</router-link>|---|
        |
        |
        |
        |
        
         <router-link to="/siderbar">Siderbar</router-link>|
    </nav>
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

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
