<template lang="pug">
.swrd-contact-info-block
  .info
    .container
      .row.stuff-top.underline
        .col-xs-6
          swrd-dept-contact-info-block(align='left')
        .col-xs-6
          swrd-etsu-contact-info-block(align='right')
</template>

<script lang="coffee">
import SwrdDeptContactInfoBlock from '@/components/SwrdDeptContactInfoBlock'
import SwrdEtsuContactInfoBlock from '@/components/SwrdEtsuContactInfoBlock'
import SwrdSiteNameInfoBlock from '@/components/SwrdSiteNameInfoBlock'
export default
  name: 'SwrdFooterAsideLinks',
  components:
    'swrd-dept-contact-info-block': SwrdDeptContactInfoBlock
    'swrd-etsu-contact-info-block': SwrdEtsuContactInfoBlock
    'swrd-site-name-info-block': SwrdSiteNameInfoBlock
</script>

<style lang="stylus" scoped>

.info
  background url('http://www.etsu.edu/etsuhome/templateimages/footer_logo_2014.png') no-repeat center 5%
  margin 0 auto
  padding-top 0
  position relative
  width 100%

.stuff-top
  padding-top 3.5em

.swrd-contact-info-block
  a
    color #7790ab
  background-color #00162e
  color: #7790ab
  padding-top 0.4em

.underline
  border-bottom 1px solid #7790ab
</style>

