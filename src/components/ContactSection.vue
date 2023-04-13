<script>
import ContactForm from './ContactForm.vue';
export default {
    name: 'ContactSection',
    components: {
        ContactForm,
    }

}

</script>

<template>
    <div class="my-container">
        <div class="d-flex  justify-content-center ">
            <div class="title">
                <h1>Let's Make Things <br>Happen</h1>
                <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Sint eos porro quod recusandae
                    aspernatur
                    similique?</span>
            </div>
            <div class="my-form">
                <ContactForm></ContactForm>

            </div>

        </div>




    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.my-container {
    background-color: black;
    color: white;
    margin: 0 auto;
    padding: 50px 0;

    .title {
        padding-right: 50px;
    }

    .my-form {
        color: black;
    }

}
</style>
