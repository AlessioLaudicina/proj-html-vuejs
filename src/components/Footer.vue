<script>
export default {
    name: 'Footer'
}

</script>

<template>
    <footer class="pt-5">
        <div class="container">
            <div class="row justify-content-end">
                <div class="col-xl-3 col-lg-4 col-md-6">
                    <div>
                        <h5>Grown Your Online Business <br> Strategically, and Improve <br> Customer Retention. </h5>
                        <div class="pt-3 d-flex justify-content-between align-items-center">
                            <fa :icon="['fab', 'facebook']" class="icon" />
                            <fa :icon="['fab', 'twitter']" class="icon" />
                            <fa :icon="['fab', 'instagram']" class="icon" />
                            <fa :icon="['fab', 'linkedin']" class="icon" />
                            <fa :icon="['fab', 'tiktok']" class="icon" />



                        </div>
                    </div>
                </div>
                <div class="col-xl-2  col-lg-3 col-md-6" style="margin-left: 100px;">
                    <div>
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
                <div class="col-xl-2 col-lg-2 col-md-6">
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
            <div class="d-flex justify-content-between" style="padding: 50px 0;">

                <div class="copyright">
                    <p>Developed by <a href="#" target="_blank">Alessio Laudicina</a></p>
                </div>
                <div class="copyright">
                    <p>Call Us (555)802-344</p>
                </div>
                <div class="copyright">
                    <p>info@business.gmail.com</p>
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

.icon {
    font-size: 20px;
}

.icon:hover {
    color: $ecstacy-cube-color;
}
</style>