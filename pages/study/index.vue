<template>
  <div>
    <MenuBar/>
    <StudyIndexBody/>
<!--    <div class="d-none d-xl-block">-->
<!--      <div class="fixed-bottom">-->
<!--        <Footer/>-->
<!--      </div>-->
<!--    </div>-->
    <div style="margin-top: 2rem;">
      <Footer/>
    </div>
  </div>
</template>

<script>
  import AppLogo from '~/components/AppLogo.vue'
  import Header from '~/components/Header.vue'
  import MenuBar from '~/components/MenuBar.vue'
  import Body from '~/components/Body.vue'
  import Footer from '~/components/Footer.vue'
  import StudyIndexBody from '~/components/StudyIndexBody.vue'

  export default {
    components: {
      AppLogo,
      Header,
      MenuBar,
      Body,
      Footer,
      StudyIndexBody,
    }
  }
</script>

<style>

  .no-margin {
    margin: 0px;
  }

</style>

