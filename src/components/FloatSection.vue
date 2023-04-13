<script>
export default {
    name: 'FloatSection'
}

</script>

<template>
    <div class="container">

        <div class="section_container">
            <div>

                <img src="../assets/images/Marketing-consulting-amico.png" alt="">

            </div>

            <div class=" d-flex flex-column title">
                <h1 class="title-column">Increase Brand <br> Awareness</h1>
                <p class="p-column">Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Aliquam, officiis.
                    Lorem ipsum dolor sit, amet consectetur <br> adipisicing elit. Aspernatur, impedit!</p>
                <button class="orangeBtn rounded">Get a Consulation</button>


            </div>

        </div>






        <div class="section_container">

            <div class=" d-flex flex-column title ">
                <h1 class="title-column"> In-House Sales <br> Training</h1>
                <p class="p-column">Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Aliquam, officiis.
                    Lorem ipsum dolor sit, <br> amet consectetur adipisicing elit. Aspernatur, impedit!</p>
                <button class="orangeBtn rounded">Get a Consulation</button>


            </div>

            <div>

                <img src="../assets/images/Marketing-consulting-bro.png" alt="">


            </div>

        </div>




        <div class="section_container">
            <div>

                <img src="../assets/images/Business-Plan-bro.png" alt="">

            </div>

            <div class="d-flex flex-column title">

                <h1 class="title-column">Harness Your <br> Social Proof </h1>
                <p class="p-column text-wrap">Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Aliquam,
                    officiis.
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. <br> Aspernatur, impedit!</p>
                <button class="orangeBtn rounded">Get a Consulation</button>


            </div>

        </div>





    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables';


.section_container {
    display: flex;
    max-width: 1170px;
    margin: 150px auto;
    height: 400px;
    justify-content: center;
    flex-wrap: wrap;

    img {
        max-width: 500px;
        height: 400px;


    }

    .title {
        margin: 0 50px;

        .p-column {
            color: black;
            line-height: 1.5em;

        }

        .orangeBtn {
            width: 200px;

        }
    }

}
</style>
