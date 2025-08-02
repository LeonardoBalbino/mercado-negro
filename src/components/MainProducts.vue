<script setup>
</script>

<template>
    <div class="products-content">
        <div class="card">
            <img src="../assets/anao-catalogo.jpg" alt="">

            <h2>Cleiton Rasta</h2>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga in explicabo neque fugiat natus voluptates
                facilis cupiditate, assumenda laudantium delectus non soluta nisi odio nihil! Perferendis consectetur
                consequatur deserunt autem?</p>
        </div>

        <div class="card">
            <img src="../assets/no-sense.webp" alt="">

            <h2>Tráfego humano (Bastante diversidade)</h2>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga in explicabo neque fugiat natus voluptates
                facilis cupiditate, assumenda laudantium delectus non soluta nisi odio nihil! Perferendis consectetur
                consequatur deserunt autem?</p>
        </div>

        <div class="card">
            <img src="../assets/traveco.enc" alt="">

            <h2>Traveco da massa</h2>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga in explicabo neque fugiat natus voluptates
                facilis cupiditate, assumenda laudantium delectus non soluta nisi odio nihil! Perferendis consectetur
                consequatur deserunt autem?</p>
        </div>
    </div>
</template>

<style scoped>
.products-content {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 20px;
    height: auto;
    justify-content: space-between;
    margin-top: -60px;
    place-items: center;

}

.card {
    display: flex;
    flex-direction: column;
    gap: 15px;
    text-align: center;
    z-index: 2;
    background-color: white;
    width: 450px;
    border-radius: 35px;
}


.card img {
    border-radius: 35px 35px 0px 0;
    height: 260px;
    object-fit: fill;
}
</style>
