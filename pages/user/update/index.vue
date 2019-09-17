<template>
  <div>
    <MenuBar/>
    <UserBody/>
<!--    <div class="d-none d-xl-block">-->
<!--      <div class="fixed-bottom">-->
<!--        <Footer/>-->
<!--      </div>-->
<!--    </div>-->
    <div style="margin-top: 3rem;">
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
  import UserBody from '~/components/UserBody.vue'

  export default {
    components: {
      AppLogo,
      Header,
      MenuBar,
      Body,
      Footer,
      UserBody,
    }
  }
</script>

<style>

  .no-margin {
    margin: 0px;
  }

</style>

