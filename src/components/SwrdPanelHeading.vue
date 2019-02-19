<template lang="pug">
.panel-heading.sw-heading
  h4.siteheading
    | Department of Social Work
    br
  p.sitesubheading College of Clinical and Rehabilitative Health Sciences
</template>

<script lang="coffee">
export default
  name: 'SwrdPanelHeading'
</script>

<style lang="stylus" scoped>
.panel-heading
  -webkit-border-radius 15px
  -moz-border-radius 15px
  border-radius 15px
  border 3px solid #ffc72c !important
  background-color #041e42 !important
  vertical-align middle

.siteheading
  font-size 130%
  padding-top 15px
  margin 0
  font-family 'sorts italic', georgia, serif

.sitesubheading
  display block
  font-size 100%
  color #fff
  margin 0
  padding 0px
  margin-top 0px
  min-width 35%
  clear both

.sw-heading
    height 85px !important
    padding 0 !important

@media only screen and (min-width: 500px)
  .sw-heading
    height 85px !important
    padding 0 !important
    background-image url('/src/assets/images/header_logo.png')
    background-position 2% 50%
    background-repeat no-repeat
  .siteheading
    float right
    display inline-block
    padding-right 20px
  .sitesubheading
    float right
    text-align right
    padding-right 20px
  .padsome
    padding-left 20px
    padding-right 20px

@media only screen and (max-width: 499px)
  .siteheading
    text-align center !important
    white-space nowrap
    vertical-align middle
    margin 0 auto
  .sitesubheading
    text-align center !important
    padding 0 !important
  .wrapcell
    white-space normal
</style>
