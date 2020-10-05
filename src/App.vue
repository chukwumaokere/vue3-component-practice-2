<template>
  <Container>
    <Logo />
    <Navbar />
    <Input placeholder="Search..." />
  </Container>
  <Footer text="Created by Chuck!" />
</template>

<script>
import Input from "./components/Input";
import Navbar from "./components/Navbar";
import Footer from "./components/Footer";
import Logo from "./components/Logo";
import Container from "./components/Container";

export default {
  components: {
    Input,
    Navbar,
    Footer,
    Logo,
    Container,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

body {
  background-color: #ececec;
}
</style>
