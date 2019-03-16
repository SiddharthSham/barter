<template>
      
  <div>
    <Header/>
    <div 
      id="hero" 
      class="container card-columns mb-5">
      <Content/>
      <Content/>
      <Content/>
    </div>
    <Footer/>
  </div>
</template>

<script>
import Header from '../components/header'
import Content from '../components/content'
import Footer from '../components/footer'

export default {
  components: {
    Header,
    Content,
    Footer
  }
}
</script>

<style lang="css" src="~/assets/main.css"/>
