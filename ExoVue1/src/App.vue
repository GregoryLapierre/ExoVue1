<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <nav class="navbar navbar-expand-sm bg-light">
      <div class="container-fluid">
        <div class="collapse navbar-collapse d-flex justify-content-around" id="navbarSupportedContent">
          <div>
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
            </ul>
          </div>
          <div>
            <button class="btn primary" type="submit"><RouterLink to="/login">Sign in</RouterLink></button>
            <button class="btn btn-outline-primary" type="submit"><RouterLink to="/about">Sign up</RouterLink></button>
          </div>
        </div>
      </div>
    </nav>

  </header>

  <RouterView />
</template>

<style scoped>

</style>
