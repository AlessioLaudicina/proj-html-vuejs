<script>
export default {
    name: 'HeaderBottom'
}

</script>

<template>
    <div class="jumbotron jumbotron-fluid h-100">
        <div class="container">
            <h1 class="display-4 text-white fw-bolder">UnlockYour Online <br>Growth Potential</h1>
            <p class="lead text-white">This is a simple hero unit, a simple jumbotron-style component, <br> for calling
                extra
                attention to
                featured content or information.</p>


            <p class="lead">
                <a class="btn  my-button" href="#" role="button">Our Services</a>
            </p>

        </div>

    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.jumbotron {
    background-image: url(../assets/images/marketing-intro.jpg);
    background-size: cover;
    min-height: 400px;

    .my-button {
        background-color: $white-cube-color;
        color: $black-cube-color;

    }

}
</style>
