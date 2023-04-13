<script>
export default {
    name: 'ContactForm'
}

</script>

<template>
    <div class="card rounded bg-white">
        <form class="d-flex flex-column justify-content-center align-items-center">
            <h5 class="text-center">Richard Madsen</h5>
            <img src="../assets/images/marketing-consultant-expert.jpg" alt="marketing-img" class="rounded-circle">
            <span class="text-center">Marketing Expert</span>
            <span class="text-center" style="color: #f76210;">
                <fa icon="fa-solid fa-phone" />
                (555) 802-1234
            </span>
            <!-- Name input -->
            <div class="form-outline mb-4">
                <input type="text" id="form5Example1" class="form-control" placeholder="Your name" />
            </div>

            <!-- Email input -->
            <div class="form-outline mb-4">
                <input type="email" id="form5Example2" class="form-control" placeholder="Your Email" />
            </div>

            <div class="form-outline mb-4">
                <input type="email" id="form5Example2" class="form-control" placeholder="Your Phone number" />
            </div>




            <!-- Submit button -->
            <button class="orangeBtn rounded">Get a Call Back</button>

        </form>

    </div>
</template>

<style lang="scss" scooped>
.card {
    width: 400px;

    padding: 30px;

    img {
        max-height: 50px;
        max-width: 50px;
    }
}
</style>