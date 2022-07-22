<script setup>
import Card from '@/components/Card.vue'
</script>




<template>
  <main>
    
    <Card>
      <h5 class="card-title text-center">Sign In</h5>
    <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" class="form-control" id="exampleFormControlInput1">
</div>
<div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">Password</label>
  <textarea class="form-control" id="exampleFormControlTextarea1" rows="1"></textarea>
</div>
<button type="button" class="btn btn-dark col-12 mb-4">Sign In</button>
  <div class="text-end">
    <a href="#" class="card-link">Forgot password ?</a>
  </div>
  <div class="text-center">
    <button type="button" class="btn col-2 bg-light my-4 "><i class="bi bi-google"></i></button>
    <button type="button" class="btn col-2 bg-light my-4"><i class="bi bi-facebook"></i></button>
    <button type="button" class="btn col-2 bg-light my-4"><i class="bi bi-twitter"></i></button>
    
  </div>
  </Card> 

  </main>
</template>
