<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header hidden>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Initial Project</a>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <RouterLink class="nav-link" aria-current="page" to="/"
                >Home</RouterLink
              >
            </li>
            <li class="nav-item">
              <RouterLink to="/signin" class="nav-link">SignIn</RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink to="/signup" class="nav-link">SignUp</RouterLink>
            </li>
            <li class="nav-item">
              <RouterLink to="/ticketform" class="nav-link">Ticket</RouterLink>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  <RouterView />
</template>

<style>
h2 {
  font-size: large;
}
</style>
