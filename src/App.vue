<template>
    <div class="app">
        <h1>hello vue2+vite</h1>
        <van-button type="primary">主要按钮</van-button>
        <van-button type="info">信息按钮</van-button>
        <van-button type="default">默认按钮</van-button>
        <van-button type="warning">警告按钮</van-button>
        <van-button type="danger">危险按钮</van-button>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/test">test</router-link>
        <router-view />


    </div>
</template>

<script>
export default {

}
</script>
<style lang="scss">
.App {
    ul {
        li {
            list-style: none;
        }
    }
}
</style>

