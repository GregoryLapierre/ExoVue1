<script setup>
import Card from '@/components/Card.vue'
</script>

<template>
  <main >
    <card>
           <h5 class="card-title text-center">Sign Up</h5>
     <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Full name</label>
  <input type="email" class="form-control" id="exampleFormControlInput1">
</div>       
    <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" class="form-control" id="exampleFormControlInput1">
</div>
<div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">Password</label>
  <textarea class="form-control" id="exampleFormControlTextarea1" rows="1"></textarea>
</div>
<button type="button" class="btn btn-dark col-12 mb-4">Sign Up</button>
  <div class="text-end">
    <p>Already Register <a href="#" class="card-link">Sign In?</a></p>
  </div>


    </card>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
  }
}
</style>
