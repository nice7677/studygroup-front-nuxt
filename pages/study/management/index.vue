<template>
  <div>
    <MenuBar/>
    <StudyManagementBody/>
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
  import StudyManagementBody from '~/components/StudyManagementBody.vue'

  export default {
    components: {
      AppLogo,
      Header,
      MenuBar,
      Body,
      Footer,
      StudyManagementBody,
    }
  }
</script>

<style>

  .no-margin {
    margin: 0px;
  }

</style>

