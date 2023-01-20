<script>

export default {
    name: 'AppHeader',

    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]
        }
    }
}
</script>

<template>

    <header>
        <nav class="container">
            <div class="nav-left">
                <img src="../assets/img/dc-logo.png" alt="dc-logo">
            </div>
            <div class="nav-right">
                <ul>
                    <li v-for="link in links" :key="link.text">
                        <a :class="{ 'active': link.current }" :href="link.url">{{ link.text }}</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

</template>

<style lang="scss" scoped>
nav {
    height: 110px;
    width: 1400;
    display: flex;

    background-color: #ffffff;
}

.nav-left {
    width: 40%;

    display: flex;
    align-items: center;

    img {
        max-width: 100%;
        height: auto;
    }
}

.nav-right {
    width: 60%;

    ul {
        height: 100%;
        display: flex;
        align-items: center;


        li {
            list-style-type: none;

            a {
                display: inline-block;
                padding: 5px;

                color: #303030;

                text-transform: uppercase;

                font-size: 11px;
                font-weight: 700;
            }
        }

    }

    .active {
        color: #0082F9;
        border-bottom: 3px solid #0082F9;
    }
}
</style>
