
<template>
  <div id="app">
<Header></Header>
    <main>
      <router-view name="slidebar"></router-view>
      <router-view name="main"></router-view>
    </main>
    <Footer></Footer>
  </div>
</template>

<script>
  import Header from './components/Header'
  import Footer from './components/Footer'
export default {
  name: 'App',
  components:{
    Header,
    Footer
  }
}
</script>

<style>
main{
  width:80%;
  margin: 0 auto;
}
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app{
  background-color: #E1E1E1;
}
</style>
