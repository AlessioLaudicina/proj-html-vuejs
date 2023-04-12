<script>
export default {
    name: 'AwardSection'
}

</script>

<template>
    <h4 class="text-center pt-4">Awards</h4>
    <div class="container">
        <div class="d-flex justify-content-center align-items-center wrap">
            <div class="awards"> <!--Inserire un v-for -->
                <img src="../assets/images/award-a.png" alt="">
                <p>Lorem ipsum dolor sit amet. <br> Lorem ipsum dolor sit amet.</p>
            </div>

            <div class="awards">
                <img src="../assets/images/award-b-200x191.png" alt="">
                <p>Lorem ipsum dolor sit amet. <br> Lorem ipsum dolor sit amet.</p>
            </div>

            <div class="awards">
                <img src="../assets/images/award-c-200x191.png" alt="">
                <p>Lorem ipsum dolor sit amet. <br> Lorem ipsum dolor sit amet.</p>
            </div>

            <div class="awards">
                <img src="../assets/images/award-d-200x191.png" alt="">
                <p>Lorem ipsum dolor sit amet. <br> Lorem ipsum dolor sit amet.</p>
            </div>


        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.awards {
    margin: 50px;
    text-align: center;

    img {
        max-width: 100px;
    }
}
</style>
