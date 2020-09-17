<template>
    <div class="header-grid">
        <img alt="Vue logo" src="../assets/logo.png" />
        <h3>About us!</h3>
        <h3>Location</h3>
       <h3>menu</h3>
    </div>
</template>

<script>
export default {
    name: "page-header"
}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
}
h3 {
    display: grid;
}
.header-grid {
    display: grid;
    justify-items: center;
    align-items: center;
    grid-template-columns: 1fr 1fr 1fr 1fr;
}
</style>