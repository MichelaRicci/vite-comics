<script lang="js">

import AppList from './AppList.vue';


export default {
    name: 'AppMain',

    components: {
        AppList,
    }
}
</script>

<template>


    <div class="content">
        <div class="container">
            <div class="gallery-container">

                <AppList />




            </div>
        </div>
    </div>

    <div class="jumbotron">

        <div class="container">
            <div class="row">
                <div class="col">
                    <div>
                        <h4>DC Comics</h4>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <h4>Shop</h4>

                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>

                    <div>
                        <h4>DC</h4>
                        <ul>
                            <li><a href="#">Therm of use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertisign</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact US</a></li>
                        </ul>
                    </div>

                    <div>
                        <h4>Sites</h4>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>
                </div>


                <div class="col">
                    <img src="../assets/img/dc-logo-bg.png" alt="dc-logo">
                </div>
            </div>
        </div>

    </div>


</template>

<style lang="scss" scoped>
.content {
    background-color: black;

    position: relative;
    z-index: 1;
}

h2 {
    line-height: 110px;
    text-align: left;
}

.jumbotron {
    background-image: url(../assets/img/footer-bg.jpg);
    height: 300px;
}

img {
    height: 400px;
}

ul {
    margin-top: 10px;

    li {
        font-size: 10px;
    }
}
</style>
