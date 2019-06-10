<template>
  <div class="body">
    <Top/>
    <div class="container no-padding">
      <Middle/>
    </div>
    <Middle2/>
    <!--    <div class="container no-padding">-->
    <Bottom/>
    <!--    </div>-->
  </div>

</template>

<script>
  import Top from '~/components/body/Top.vue'
  import Middle from '~/components/body/Middle.vue'
  import Middle2 from '~/components/body/Middle2.vue'
  import Bottom from '~/components/body/Bottom.vue'


  export default {
    components: {
      Top,
      Middle,
      Middle2,
      Bottom
    },
    name: "Body"
  }
</script>

<style scoped>
  .body {
    margin-top: 4rem;
    /*margin-bottom: 1rem;*/
  }
</style>
