<script>
import ContactForm from './ContactForm.vue';
export default {
    name: 'HeaderBottom',
    components: {
        ContactForm
    }
}

</script>

<template>
    <div class="jumbotron jumbotron-fluid h-100">
        <div class="container">
            <div class="d-flex flex-wrap justify-content-center align-items-center">
                <div class="intro">
                    <h1 class="display-4 text-white fw-bolder pt-4">UnlockYour Online <br>Growth Potential</h1>
                    <p class="lead text-white">This is a simple hero unit, a simple jumbotron-style component, <br> for
                        calling
                        extra
                        attention to
                        featured content or information.</p>


                    <p class="lead">
                        <a class="btn  my-button" href="#" role="button">Our Services
                            <fa icon="fa-solid fa-arrow-right" />
                        </a>
                    </p>

                </div>

                <div class="contact-form">
                    <ContactForm></ContactForm>
                </div>
            </div>

        </div>



    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.jumbotron {
    background-image: url(../assets/images/marketing-intro.jpg);

    background-size: cover;
    min-height: 400px;

    .intro {
        padding-right: 50px;
    }

    .my-button {
        background-color: $white-cube-color;
        color: $black-cube-color;
        padding: 10px;

    }

    .contact-form {
        padding-top: 50px;
        position: relative;
        bottom: -60px;
    }



}
</style>
