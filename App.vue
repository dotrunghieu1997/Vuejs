<template>
  <div id="app">
    <nav class="navbar navbar-expand-sm bg-primary navbar-dark" id="navbar">
    <!-- Brand -->
    <a class="navbar-brand" href="#">Home</a>
    <!-- Toggler/collapsibe Button -->
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
    </button>
    <!-- Navbar links -->
    <div class="collapse navbar-collapse" id="collapsibleNavbar">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="#">Shop</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Card</a></li>
      </ul>
    </div> 
  </nav>
  <router-view />
  </div>
</template>


<style>
#navbar {
    height: 60px;
}
</style>
