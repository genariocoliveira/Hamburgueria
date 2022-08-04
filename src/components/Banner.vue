<template>
    <div id="main-banner">
        <h1>The Burger</h1>
    </div>
</template>

<script>
export default {
    mame: 'Banner'
}
</script>

<style scoped>

#main-banner{
    background: url('../assets/burger.jpg') no-repeat;
    background-position: 0 -250px;
    background-size: cover;
    height: 800px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}
#main-banner h1{
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 20px 40px;
}
</style>