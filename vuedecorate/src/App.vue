<template>
  <div id="app">
    <div class="container">
      <nav class="navbar navbar-dark bg-inverse navbar-fixed-top">
        <router-link to="/" class="navbar-brand text-success">检测室</router-link>
        <ul class="nav-item">
          <router-link to="/home" class="nav-link"/>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>

  import Siderbar from './components/Sidebar.vue'

  export default {
    name: 'App',
    'sidebar': Siderbar
  }

</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
