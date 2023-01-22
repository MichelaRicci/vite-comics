<script>

export default {
    name: 'AppFooter',
    data() {
        return {
        }
    }
}

</script>

<template>

    <footer>
        <div class="container">
            <div class="row">

                <div class="col">
                    <div class="btn">
                        <h3><a href="#">Sign-up now!</a></h3>
                    </div>
                </div>

                <div class="col-right">
                    <div>
                        <h3>Follow Us</h3>
                    </div>
                    <ul>
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="YouTube"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="Periscope"></a></li>
                    </ul>
                </div>
            </div>
        </div>

    </footer>

</template>

<style lang="scss" scoped>
footer {
    height: 110px;
    background-color: #303030;
}

.row {
    height: 110px;
}

.col {

    .btn {
        justify-content: flex-start;

        border: 2px solid #0082F9;

        padding: 15px;

        a {
            display: inline-block;
            color: #ffffff;
            font-weight: 700;
        }
    }
}

.col-right {
    width: 50%;
    color: #0082F9;
    display: flex;
    align-items: center;

    ul {

        display: flex;

        align-self: center;

        li {
            margin: 0 5px;

            a {
                padding-right: 10px;
            }
        }
    }
}
</style>
