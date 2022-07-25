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
import Nav from "./homePage/Nav";
import Header from "./homePage/Header";
import Aside from "./homePage/Aside";
import Main from "./homePage/Main";
import Footer from "./homePage/Footer";
export default {
  components: {
    Nav,
    Header,
    Aside,
    Main,
    Footer,
  },
  name: "homePage",
};
</script>

<style>
</style>