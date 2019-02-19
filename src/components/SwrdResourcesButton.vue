<template lang="pug">
.swrd-resources-button
  .col-xs-6.col-sm-6.col-md-4.col-lg-3
    a(href='resources.html')
      img.imglink(src='../assets/images/lightbulb.png' alt='Resources')
    h3.footerlink
      a(href='resources.html') Resources
</template>

<script lang="coffee">
export default
  name: 'SwrdResourcesButton'
</script>

<style lang="stylus" scoped>
.footerlink
  width 100%
  margin-top 0px
  margin-bottom 20px
  text-align center
  color #7790ab
  text-decoration underline
</style>
