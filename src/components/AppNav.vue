<template>
<nav class="navbar navbar-white bg-white shadow-sm bg-body rounded">
  <div class="container-fluid">
    <a class="navbar-brand text-dark">Professional CV Home</a>
      <div class="navbar me-5">
        <router-link class="nav-link text-dark"  to="/">Home</router-link>
        <router-link class="nav-link text-dark" to="/about">Experience</router-link>
        <router-link class="nav-link text-dark" to="/my-work">My work</router-link>
      </div>        
  </div>
</nav>    
</template>

<style scoped>
.nav-link.text-dark.router-link-exact-active.router-link-active{
  color: #42b983 !important;
}
</style>
