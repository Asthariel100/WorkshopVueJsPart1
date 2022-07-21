<script setup>
    import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <nav class="navbar navbar-light bg-light">
    <form class="container-fluid justify-content-end">
        <RouterLink to="/signin"><button class="btn btn-outline-success me-2" type="button">Sign in</button></RouterLink>
        <RouterLink to="/signup"><button class="btn btn-sm btn-outline-secondary" type="button">Register</button></RouterLink>
    </form>
    </nav>
</template>

