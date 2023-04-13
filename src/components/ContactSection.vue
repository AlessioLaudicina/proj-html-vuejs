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
                <h1 class="py-4" style="font-size: 60px;">Let's Make Things <br>Happen</h1>
                <span class="py-4" style="font-size: 25px; text-align: left;">Lorem ipsum dolor sit amet consectetur
                    adipisicing elit.

                    <br> Sint eos porro
                    quod recusandae
                    aspernatur
                    similique? <br>adipisicing elit.</span>

                <p class="pt-4">"The team at Avada Consulting is fabolous. They<br> helped us unlock our potential online
                    and offline.
                    We have <br> experience year on year due to their <br> progressive approch. "</p>

                <p><strong>George Anderson</strong></p>
                <p>Digital Box CEO</p>
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
