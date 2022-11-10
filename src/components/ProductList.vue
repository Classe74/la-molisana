<template>
    <section class="products">
        <div class="container">
            <h1>Prodotti</h1>
            <div class="row">
                <div class="col">
                    <img src="https://www.lamolisana.it/wp-content/uploads/2021/04/1-spaghetto-quadrato.jpg" alt="">
                </div>
                <div class="col">
                    <img src="https://www.lamolisana.it/wp-content/uploads/2021/04/1-spaghetto-quadrato.jpg" alt="">
                </div>
                <div class="col">
                    <img src="https://www.lamolisana.it/wp-content/uploads/2021/04/1-spaghetto-quadrato.jpg" alt="">
                </div>
                <div class="col">
                    <img src="https://www.lamolisana.it/wp-content/uploads/2021/04/1-spaghetto-quadrato.jpg" alt="">
                </div>
                <div class="col">
                    <img src="https://www.lamolisana.it/wp-content/uploads/2021/04/1-spaghetto-quadrato.jpg" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ProductList'
}
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/mixins' as *;
@use '../assets/styles/partials/variables' as *;


.products {
    padding: 2rem 1rem;
    text-align: center;
    background-image: url("../assets/img/fondo-pag-speciali.jpg");


    h1 {
        color: $bluetext;
        margin-bottom: 20px;
    }

    .row {
        @include dflex;

        .col {
            flex-basis: calc(100% / 4);
            padding: 2rem;
        }
    }

}
</style>