<template>
    <div class="container">
        <h2>It looks like you are looking for a page that's not here.</h2>
        <p>Take a look at our <router-link to=/search-page>Search page</router-link>. You might find what you are looking for there.</p>
    </div>
</template>

<style scoped>
.container {
    max-width: 100%;
    height: 700px;
}

h2, p {
    text-align: center;
}

h2 {
    padding-top: 2%;
}
</style>