<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
<div class="about">
<div>
  <div class="container">
    <div class="row">
        <div>
            <h1>Register</h1>
        </div>     
        <div class="col-md-6">
            <div class="row">
                <div class="mb-3">
                    <label for="exampleFormControlInput1" class="form-label">Full name</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Full name">
                </div>
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Email">
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Password</label>
                <input type="password" class="form-control" id="exampleFormControlInput1" placeholder="password">
            </div>
            <div class="row">
                <div class="col-md-2">
                    <RouterLink to="/signin"><button type="button" id="myInput" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#myModal">
                        Go
                      </button></RouterLink>
                </div>
            </div>
        </div>
    </div>
  </div>
</div>
</div>

</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
    background-color: blue;
  }
}
</style>
