<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/todos">Todos</router-link> |
      <router-link to="/issues">Issues</router-link> |
      <!--Ajouter à partir de "|" sur le côté droit ci-dessous-->
      <router-link to="/todos-issues">Todos-Issues</router-link> |
      <router-link to="/tasks">Tasks</router-link>
      <!--Ajouter ici-->
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
</style>
