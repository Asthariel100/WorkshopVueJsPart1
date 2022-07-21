<template>
<div class="about">
<div>
  <div class="container">
    <div class="row">
        <div>
            <h1>Mot de passe oublié</h1>
        </div>     
        <div class="col-md-6">
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email address</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Email">
            </div>
            <div class="row">
                <div class="col-md-2">
                    <button type="button" id="myInput" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#myModal">
                        Recuperer
                      </button>
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
