<template>
<div class="container">
    <div class="header">
        vuejs
    </div>

    <mt-button type="default" class="mint" @click="jumpCenter">next</mt-button>
</div>
</template>

<script>
export default {
    data: function () {
        return {}
    },
    methods: {
        jumpCenter() {
            console.log("home");
            // this.$router.replace('/test/home')
            this.$router.push('/test/home')
        }
    }
}
</script>

<style lang="scss" scoped>
.container {
    height: 100%;
    background: blue;
    text-align: center;

    .header {
        width: 100%;
        height: 250px;
        background: red;
        font-size: 45px;

    }

    .btn {
        font-size: 45px;
        width: 300px;
        margin: 50px 0 0 0;
    }

    .mint {
        // font-size: 45px;
        width: 300px;
        margin: 50px 0 0 0;
        background: white
    }

}
</style>
