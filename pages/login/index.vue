<template>
  <div>
    <MenuBar/>
    <LoginBody/>
    <div class="fixed-bottom">
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
  import LoginBody from '~/components/LoginBody.vue'

  export default {
    components: {
      AppLogo,
      Header,
      MenuBar,
      Body,
      Footer,
      LoginBody,
    }
  }
</script>

<style>

  .no-margin {
    margin: 0px;
  }

</style>

