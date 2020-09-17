<template>
    <div class="body-grid">
        <aside class="sidebar">
        <h3>Meet the Team!!</h3>
        <h3>Meet your Developers!</h3>
        </aside>
        </div>
</template>

<script>

export default {
    name: "page-body",

}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
}
h3{
    display:grid;

}
.body-grid {
    display: grid;
    justify-items: center;
    align-items: center;
    grid-template-columns:  3fr 3fr;
}
</style>