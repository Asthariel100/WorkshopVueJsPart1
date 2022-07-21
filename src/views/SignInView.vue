<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
<div class="about">
<div>
  <div class="container">
    <div class="row">
        <div>
            <h1>Connection</h1>
        </div>     
        <div class="col-md-6">
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Email">
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Password</label>
                <input type="password" class="form-control" id="exampleFormControlInput1" placeholder="password">
            </div>
            <div class="row">
                <div class="col-md-6">
                    <button type="button" id="myInput" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#myModal">
                        Se connecter
                      </button>
                </div>
                <div class="col-md-6">
                    <RouterLink to="/password"><button class="btn btn-outline-success" type="button">Mot de passe oublié</button></RouterLink>
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
