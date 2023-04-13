<script>
export default {
    name: 'BrandSection'
}

</script>

<template>
    <div class="container">
        <h1 class="text-center fw-bolder">Some Brands We Work With</h1>
        <p class="text-center">Lorem ipsum dolor sit amet lorem amamet.</p>

        <div class="d-flex justify-content-center align-items-center p-4">

            <img src="../assets/images/abstract.png" alt="" srcset="">
            <img src="../assets/images/cglobal.png" alt="" srcset="">
            <img src="../assets/images/next.png" alt="" srcset="">
            <img src="../assets/images/hemisferio.png" alt="" srcset="">
            <img src="../assets/images/spaces.png" alt="" srcset="">
            <img src="../assets/images/digitalbox.png" alt="" srcset="">



        </div>
        <div class="container">
            <div class="shadow p-3 rounded d-flex justify-content-around align-items-center"
                style="margin: 100px 0; max-height: 75px;">
                <img src="../assets/images/marketing-expert-cta.png" style="max-height: 50px; border-radius: 100%;">
                <p> <strong>Sandy Reiff </strong><br> <span>Marketing Expert</span></p>
                <h5>Drive Leads and Sales with Avada</h5>
                <button class="lightorangeBtn rounded">
                    <fa icon="fa-solid fa-phone" /> (555) 802-1234
                </button>

            </div>

        </div>




    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

img {
    max-width: 100px;
    margin: 0 15px;
}
</style>
