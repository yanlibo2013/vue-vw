<template>
<div class="container">
    <div class="header">
        home
    </div>

    <mt-button type="default" class="mint " @click="jumpCenter">back</mt-button>
</div>
</template>

<script>
1
export default {
    data: function () {
        return {}
    },
    methods: {
        jumpCenter() {
           this.$router.go(-1);
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
        background:white
    }

}
</style>
