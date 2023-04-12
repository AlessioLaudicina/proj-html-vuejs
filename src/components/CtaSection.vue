<script>
export default {
    name: 'CtaSection'
}

</script>

<template>
    <div class="my-container">
        <div class="container d-flex justify-content-center">
            <div class="section_container py-5">

                <div class="big-column d-flex flex-column">
                    <h1 class="title-column text-left"> We Boost Our <br> Clients' Bottom Line <br> by Optimizing Their <br>
                        Growth
                        Potential.</h1>
                    <p class="p-column">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nisi, quidem </p>
                    <button class="orangeBtn rounded">Get a Consulation</button>


                </div>

                <div class="small-column">

                    <img src="../assets/images/we-boost-our-clients-400x366.jpg" alt="" class="rounded">


                </div>

            </div>
        </div>

        <div class="d-flex justify-content-center">
            <div class="title">
                <h3>We Build Relationship</h3>
                <span class="p-column">Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam consequuntur dolorum
                    eligendi officia reiciendis nostrum.</span>
                <h3>Propriarty Process</h3>
                <p class="p-column">Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam consequuntur dolorum
                    eligendi officia reiciendis nostrum.</p>
            </div>
            <div class="icon">
                <h4>Accountability</h4>
                <p class="p-column"> Numquam consequuntur dolorum eligendi officia reiciendis nostrum.</p>


            </div>
        </div>

    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.my-container {
    background-color: whitesmoke;
    margin: 0 auto;

}

.section_container {
    display: flex;
    max-width: 1170px;
    margin: 150px auto;
    height: 400px;


}

.small-column {
    width: 50%;


}

.big-column {
    width: 50%;
}






.p-column {
    color: $gunsmoke-cube-color;
    line-height: 1.5em;
    padding-right: 30px;


}
</style>
