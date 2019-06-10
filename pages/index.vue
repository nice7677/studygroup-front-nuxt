<template>
  <div>
    <MenuBar/>
    <Body/>
    <Footer/>
  </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Header from '~/components/Header.vue'
import MenuBar from '~/components/MenuBar.vue'
import Body from '~/components/Body.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    AppLogo,
    Header,
    MenuBar,
    Body,
    Footer,
  }
}
</script>

<style>

  .no-margin {
    margin: 0px;
  }
/*.container {*/
/*  min-height: 100vh;*/
/*  display: flex;*/
/*  justify-content: center;*/
/*  align-items: center;*/
/*  text-align: center;*/
/*}*/

/*.title {*/
/*  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; !* 1 *!*/
/*  display: block;*/
/*  font-weight: 300;*/
/*  font-size: 100px;*/
/*  color: #35495e;*/
/*  letter-spacing: 1px;*/
/*}*/

/*.subtitle {*/
/*  font-weight: 300;*/
/*  font-size: 42px;*/
/*  color: #526488;*/
/*  word-spacing: 5px;*/
/*  padding-bottom: 15px;*/
/*}*/

/*.links {*/
/*  padding-top: 15px;*/
/*}*/
</style>

