<script>
export default {
    name: 'Footer'
}

</script>

<template>
    <footer class="pt-5">
        <div class="container">
            <div class="row">
                <div class="col-xl-3 col-lg-4 col-md-6">
                    <div>
                        <h5>Grown Your Online Business <br> Strategically, and Improve <br> Customer Retention. </h5>
                        <div class="icons">

                        </div>
                    </div>
                </div>
                <div class="col-xl-2 offset-xl-1 col-lg-2 col-md-6">
                    <div class="">
                        <h6>Services</h6>
                        <ul class="list-unstyled">
                            <li>
                                Home
                            </li>
                            <li>
                                About Us
                            </li>
                            <li>
                                Service
                            </li>
                            <li>
                                Contact
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-xl-3 col-lg-3 col-md-6">
                    <div>
                        <h6>Resource</h6>
                        <ul class="list-unstyled">
                            <li>
                                Marketing Plan
                            </li>
                            <li>
                                Sales Development
                            </li>
                            <li>
                                Digital Marketing
                            </li>
                            <li>
                                Pricing
                            </li>
                            <li>
                                Why Us
                            </li>
                            <li>
                                Case Studies
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-xl-3 col-lg-3 col-md-6">
                    <div>
                        <h6>Company</h6>
                        <ul class="list-unstyled">
                            <li>
                                Who we are
                            </li>
                            <li>
                                Contact Us

                            </li>
                            <li>
                                Carriers
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="d-flex justify-content-center">

                <div class="copyright">
                    <p>Developed by <a href="#" target="_blank">Alessio Laudicina</a></p>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scooped >
@use '../styles/partials/variables' as *;

ul {
    padding-top: 10px;

    li {

        padding: 5px;
        cursor: pointer;
    }

    li:hover {
        color: $ecstacy-cube-color;
    }
}
</style>