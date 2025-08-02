<script setup>
</script>

<template>
    <div class="header">
        <div class="menu">
            <h1>Mercado negro</h1>

            <div class="search-box">
                <input type="text" placeholder="Buscar miniaturas, mãe solteiras,anões e escravos...">

                <img class="search" src="@/assets/search.svg" alt="">
            </div>

            <img class="anao-alargado" src="@/assets/anao.webp" alt="">
        </div>
    </div>
</template>

<style scoped>
.header {
    background-color: black;
    height: 40vh;
    width: 100%;
    display: flex;
    justify-content: center;
    position: relative;
}

.header .anao-alargado {
    position: absolute;
    right: 0;
    top: 0;
    z-index: -1;
    height: 40vh;
    width: 71%;
}

.search-box {
    position: relative;
}

.search {
    position: absolute;
    right: -5px;
    top: 7px;
}

.menu {
    color: white;
    width: 100%;
    height: 40px;
    align-items: center;
    gap: 100px;
    display: grid;
    grid-template-columns: 300px 60% 1fr;
    padding: 15px;
    z-index: 2;
}

.menu h1 {
    flex-wrap: nowrap;
}

.menu input {
    color: rgba(0, 0, 0, .8980392157);
    font-size: 16px;
    margin: 0;
    font-family: inherit;
    border-radius: 2px;
    background-color: #fff;
    display: flex;

    box-shadow: 0 1px 2px 0 rgba(0, 0, 0, .2);
    height: 20px;
    width: 100%;
    padding: 10px;
    border-style: solid;
    border-color: rgba(0, 0, 0, 0);
    border-width: 1.5px;

}
</style>
