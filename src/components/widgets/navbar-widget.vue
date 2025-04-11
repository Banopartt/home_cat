<template>
    <header class="header">
        <div class="logo">
            Котейка
        </div>
        <nav class="hidden md:flex gap-7 items-center">
            <a href="why">Почему мы?</a>
            <a href="rooms">Номера</a>
            <a href="reviews">Отзывы</a>
            <a href="contact">Как нас найти</a>
        </nav>
    </header>
</template>

<script setup>

</script>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 40px;
    width: 100%;
}

.logo {
    font-size: 20px;
    text-decoration: none;
    color: #1A212F;
    font-weight: 500;
    transition: color 0.2s;
}

.nav a:hover {
    color: #1A212F;
}

a {
    color: #1A212F;
}
</style>