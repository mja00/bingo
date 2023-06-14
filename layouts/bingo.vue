<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/bingo">Bingo Games</NuxtLink>
            </nav>
        </header>

        <div>
            <slot />
        </div>

        <footer>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/bingo/test">Bingo</NuxtLink></li>
            </ul>
        </footer>
    </div>
</template>

<style scoped>
.router-link-exact-active {
    color: seagreen;
}
</style>