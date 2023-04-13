<script>
import AwardSection from './AwardSection.vue';
export default {
    name: 'CtaSection',
    components: {
        AwardSection
    }
}

</script>

<template>
    <div class="my-container">
        <div class="container d-flex justify-content-center flex-wrap">
            <div class="section_container py-5">

                <div class=" d-flex flex-column">
                    <h1 class="title-column text-left"> We Boost Our <br> Clients' Bottom Line <br> by Optimizing Their <br>
                        Growth
                        Potential.</h1>
                    <p class="p-column">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nisi, quidem </p>
                    <button class="orangeBtn rounded">Get a Consulation</button>


                </div>

                <div>

                    <img src="../assets/images/we-boost-our-clients-400x366.jpg" alt="" class="rounded">


                </div>

            </div>
            <div class="d-flex justify-content-center">
                <div class="title">
                    <h3>We Build Relationship</h3>
                    <span class="p-column">Lorem ipsum dolor sit amet consectetur <br> adipisicing elit. Numquam
                        consequuntur
                        dolorum
                        eligendi officia reiciendis nostrum.</span>
                    <h3>Propriarty Process</h3>
                    <span class="p-column">Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Numquam
                        consequuntur
                        dolorum
                        eligendi officia reiciendis nostrum.</span>
                </div>
                <div class="icon">
                    <ul>
                        <li>
                            <h4>Accountability</h4>
                            <p class="p-column"> Numquam consequuntur dolorum eligendi.</p>
                        </li>
                        <li>
                            <h4>Accountability</h4>
                            <p class="p-column"> Numquam consequuntur dolorum eligendi.</p>
                        </li>
                        <li>
                            <h4>Accountability</h4>
                            <p class="p-column"> Numquam consequuntur dolorum eligendi.</p>
                        </li>
                    </ul>





                </div>
            </div>

        </div>


        <AwardSection></AwardSection>

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







.p-column {
    color: $gunsmoke-cube-color;
    line-height: 1.5em;
    padding-right: 30px;


}</style>
