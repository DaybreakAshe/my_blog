<template>
<div>
    <Nav></Nav>
    <Header></Header>
    <Aside></Aside>
    <Main></Main>
    <Footer></Footer>
</div>
</template>

<script>
// 引入该页面的各部分组件
import Nav from "./homePage/Nav.vue";
import Header from "./homePage/Header.vue";
import Aside from "./homePage/Aside.vue";
import Main from "./homePage/Main.vue";
import Footer from "./homePage/Footer.vue";
export default {
    components: {
        Nav,
        Header,
        Aside,
        Main,
        Footer
    },
    name:'homePage'
};
</script>

<style>
</style>