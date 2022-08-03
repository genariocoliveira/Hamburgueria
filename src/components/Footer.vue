<template>
    <div class="footer">
        <div class="main-footer">
            <p>Todos os direitos reservados &copy; 2022</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped>
.footer{
    position: absolute;
    bottom: 0;
    width: 100%;
}
.main-footer{
    height: 50px;
    padding: 20px 0;
    background: #222;
    border-top: 4px solid #111;
    color: #fcba03;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
}

</style>