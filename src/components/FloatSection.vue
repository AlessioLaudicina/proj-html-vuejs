<script>
export default {
    name: 'FloatSection'
}

</script>

<template>
    <div class="container">
        <section class="container">
            <div class="section_container">
                <div class="big-column">

                    <img src="../assets/images/yoga_demo-400x300.jpg" alt="">

                </div>

                <div class="small-column d-flex flex-column">
                    <h1 class="title-column">Increase Brand <br> Awareness</h1>
                    <p class="p-column">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam, officiis.</p>
                    <button class="orangeBtn rounded">Get a Consulation</button>


                </div>

            </div>

        </section>

        <section class="container">


            <div class="section_container">

                <div class="big-column d-flex flex-column">
                    <h1 class="title-column"> In-House Sales <br> Training</h1>
                    <p class="p-column">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nisi, quidem </p>
                    <button class="orangeBtn rounded">Get a Consulation</button>


                </div>

                <div class="small-column">

                    <img src="../assets/images/yoga_demo-400x300.jpg" alt="">


                </div>

            </div>

        </section>

        <section class="container">
            <div class="section_container">
                <div class="big-column">

                    <img src="../assets/images/yoga_demo-400x300.jpg" alt="">

                </div>

                <div class="small-column d-flex flex-column">

                    <h1 class="title-column">Harness Your <br> Social Proof </h1>
                    <p class="p-column">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam, officiis.</p>
                    <button class="orangeBtn rounded">Get a Consulation</button>


                </div>

            </div>

        </section>



    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables';

.section_container {
    display: flex;
    max-width: 1170px;
    margin: 150px auto;
    height: 400px;


}





.p-column {
    color: black;
    line-height: 1.5em;
    font-size: 20px;

}
</style>
