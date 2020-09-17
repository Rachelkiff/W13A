<template>
    <div class="footer-grid">
        <h3>Jobs</h3>
        <h3>Support</h3>
        <h3>Terms of service</h3>
        
    </div>
</template>

<script>
export default {
    name: "page-footer"
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
.footer-grid {
    display: grid;
    justify-items: grid;
    align-items: grid;
    grid-template-columns: 2fr 2fr 2fr;
}
</style>