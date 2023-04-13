<script>
export default {
    name: 'HeaderTop'
}

</script>

<template>
    <div class="container">
        <div class="My-navbar">
            <ul>
                <li><img src="../assets/images/avada-marketing-logo-2x-200x37.png" alt=""></li>
                <li><a href="#">Home</a> </li>
                <li> <a href="#">Services</a> </li>
                <li> <a href="#">Why us</a></li>
                <li> <a href="#">Case Studies</a></li>
                <li> <a href="#">About</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">
                        <fa icon="fa-solid fa-phone" />
                    </a> (555) 802-1234</li>
                <li> <a href="#"><button class="btn">
                            Join
                            Us
                        </button></a></li>
            </ul>
        </div>

    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.My-navbar {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px;

    ul {
        display: flex;
        justify-content: center;
        align-items: center;

        li {
            margin: 0 10px;
            list-style: none;

            a {
                list-style: none;
                text-decoration: none;
                color: $black-cube-color;
            }

            a:hover {
                color: $ecstacy-cube-color;
            }
        }
    }
}
</style>
