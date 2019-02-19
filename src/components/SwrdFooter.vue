<template lang="pug">
.swrd-footer
  swrd-mountains-graphic
  .info-block
    swrd-contact-info-block
    swrd-site-name-info-block.move-up
    swrd-copyright-privacy-info-block.stuff-top
</template>

<script lang="coffee">
import SwrdContactInfoBlock from '@/components/SwrdContactInfoBlock'
import SwrdMountainsGraphic from '@/components/SwrdMountainsGraphic'
import SwrdCopyrightPrivacyInfoBlock from '@/components/SwrdCopyrightPrivacyInfoBlock'
import SwrdSiteNameInfoBlock from '@/components/SwrdSiteNameInfoBlock'
export default
  name: 'SwrdFooter',
  components:
    'swrd-contact-info-block': SwrdContactInfoBlock
    'swrd-mountains-graphic': SwrdMountainsGraphic
    'swrd-copyright-privacy-info-block': SwrdCopyrightPrivacyInfoBlock
    'swrd-site-name-info-block': SwrdSiteNameInfoBlock
</script>

<style lang="stylus" scoped>
.info-block
  background-color #00162e
  color #7790ab
  padding 0 0 5.0em
  position relative

.move-up
  margin-top -3.0em

.stuff-top
  padding-top 1.0em
</style>
