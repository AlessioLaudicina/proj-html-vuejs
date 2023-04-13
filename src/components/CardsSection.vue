<script>
export default {
    name: 'CardsSection'
}

</script>

<template>
    <h2 class="text-center">Trusted By Leading Organisations</h2>
    <div class="container">
        <div class="d-flex justify-content-center">
            <div class="card m-4 border-0" style="width: 18rem;"> <!--Devo aggiungere un v-for-->
                <img class="card-img-top" src="../assets/images/case-studies-1-400x450.jpg" alt="Card image cap">
                <div class="card-body">
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                    <h3>200%</h3>
                    <span>High revenue from digital</span>

                </div>
            </div>
            <div class="card m-4 border-0" style="width: 18rem;">
                <img class="card-img-top" src="../assets/images/case-studies-4-400x450.jpg" alt="Card image cap">
                <div class="card-body">
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>

                    <h3>10x</h3>
                    <span>Sales Increase with the same ad spend</span>

                </div>
            </div>
            <div class="card m-4 border-0" style="width: 18rem;">
                <img class="card-img-top" src="../assets/images/case-studies-6-400x450.jpg" alt="Card image cap">
                <div class="card-body">
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>

                    <h3>3-Years</h3>
                    <span>Partenship with Avada Consultant</span>

                </div>
            </div>

        </div>
        <div class="d-flex justify-content-center my-3">
            <button class="orangeBtn rounded pb-3">Read More Cases Studies</button>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.card-text {
    font-size: 16px;
}

.card-img-top:hover {
    opacity: 0.8;
}
</style>
