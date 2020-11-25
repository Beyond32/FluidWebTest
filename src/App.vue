<template>

<div id="app">
   <Header/>
  <CardSection/>
  <OurSpecialities/>
  <BlockMenuImgs/>
  <ShashlikBg/>
  <MenuList/>
  <Location/>
  <Footer/>
</div>
 
</template>

<script>
import Header from"./components/Header.vue"
import CardSection from "./components/CardSection.vue"
import OurSpecialities from "./components/OurSpecialities"
import BlockMenuImgs from "./components/BlockMenuImgs"
import ShashlikBg from "./components/ShashlikBg"
import MenuList from "./components/MenuList"
import Location from "./components/Location"
import Footer from "./components/Footer"
export default {
  name: 'App',
  components: {
    Header,
    CardSection,
    OurSpecialities,
    BlockMenuImgs,
    ShashlikBg,
    MenuList,
    Location,
    Footer
  }
}
</script>

<style>

</style>
