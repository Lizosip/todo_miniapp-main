<template>
 <nav class="navbar">
    <router-link to="/" class="nav-link">Задачи</router-link>
    <router-link to="/profile" class="nav-link">Профиль</router-link>
 </nav>
</template>


<script>
export default {
    name: "Navbar"
}
</script>

<style scoped>
.navbar {
    display: flex;
    justify-content: space-around;
    aligh-atems: center;
    height: 60px;

.nav-link{
    text-decoration: none;
    color: #333;
    font-size: 16px;
    font-weight: 500;
}
}
</style>