<template>
  <div class="wrapper">
  <header class="header">
    <my-header></my-header>
  </header>
  <main class="main-content">
    <article class="container"></article>
  </main>
  <footer class="footer">
    <my-footer></my-footer>
  </footer>
</div>
</template>

<script>
import MyFooter from './components/MyFooter.vue';
import MyHeader from './components/MyHeader.vue';
export default {
  components: {
    MyHeader,
    MyFooter
  },
  data() {


    return {

    }
  },
  methods: {
  }
}
</script>

<style lang="css" >
*{
  margin: 0;
  font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
  font-size: 17px;
}
body{
  margin: 0;
  position: relative;
  left: 0;
  top: 0;
}
html{
  height: 100%;
}
.container {
  width: 90%;
  margin: 0 auto;
}

header,
footer {
  display: flex;
  align-items: center;
  margin: 0;
  height: 80px;
  padding: 0 15px;
  background: #e3e0bd6b;
  flex-shrink: 0 ;
}

.wrapper{
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
main{
  flex-grow: 1;
}
</style>