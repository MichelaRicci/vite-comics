<script>
export default {
    name: 'AppCard',
    data() {
        return {
        }
    },
    props: {
        img: String,
        title: String
    }
}
</script>

<template>

    <div class="card">
        <img :src="img" :alt="title">
        <h4>{{ title }}</h4>
    </div>

</template>

<style lang="scss" scoped>
.card {
    width: 15%;
    color: white;
    text-align: center;

    margin: 10px;

    img {

        width: 100%;

    }
}
</style>