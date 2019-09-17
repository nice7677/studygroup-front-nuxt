<template>
  <div>
    <MenuBar/>
    <NoticeBody/>
    <!--    <div class="d-none d-xl-block">-->
    <div class="fixed-bottom">
      <Footer/>
    </div>
    <!--    </div>-->
    <!--    <div class="d-block d-sm-none" style="margin-top: 6rem;">-->
    <!--      <Footer/>-->
    <!--    </div>-->
  </div>
</template>

<script>
  import AppLogo from '~/components/AppLogo.vue'
  import Header from '~/components/Header.vue'
  import MenuBar from '~/components/MenuBar.vue'
  import Body from '~/components/Body.vue'
  import Footer from '~/components/Footer.vue'
  import NoticeBody from '~/components/NoticeBody.vue'

  export default {
    components: {
      AppLogo,
      Header,
      MenuBar,
      Body,
      Footer,
      NoticeBody,
    }
  }
</script>

<style scoped>

</style>
