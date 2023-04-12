<script>
export default {
    name: 'MarketingSection',

}

</script>

<template>
    <div class="my-container">
        <div class="d-flex justify-content-around align-items-center">
            <h1>Marketing Resources: <br> Inside Advisor on How to <br> Increase Online Sales</h1>
            <button class="orangeBtn rounded">Explore All Resources</button>
        </div>
        <div class="d-flex justify-content-center align-items-center">
            <div class="m-3"> <!--Aggiungere un v-for -->
                <img src="../assets/images/blog-posts-3-400x267.jpg" alt="">
                <p>Marketing Tips and Tricks</p>
            </div>
            <div class="m-3">
                <img src="../assets/images/blog-posts-4-400x267.jpg" alt="">
                <p>Marketing Tips and Tricks</p>
            </div>
            <div class="m-3">
                <img src="../assets/images/blog-posts-5-400x267.jpg" alt="">
                <p>Marketing Tips and Tricks</p>
            </div>
        </div>



    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.my-container {
    background-color: whitesmoke;
    margin: 0 auto;
    padding: 50px 0;

}
</style>
