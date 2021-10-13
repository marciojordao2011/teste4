<template>
    <div id="main-banner">
        <h1>Make yout Burguer</h1>
    </div>
</template>

<script>


export default {
    name: "Banner"
}
</script>

<style scoped>
    #main-banner {
        background-image: url('/img/realista.jpg');
        background-position: 0 -250px;
        background-size: cover;
        height:700px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }
    #main-banner h1 {
        color:aliceblue;
        text-align: center;
        font-size:60px;
        background-color:#222;
        padding: 20px 40px;

    }
</style>