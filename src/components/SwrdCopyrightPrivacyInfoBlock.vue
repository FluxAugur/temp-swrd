<template lang="pug">
.swrd-copyright-privacy-info-block
  p
    | &copy; 2016 All Rights Reserved
  p
    a(href='http://www.etsu.edu/etsuhome/documents/webprivacystatement.pdf') Privacy Policy
</template>

<script lang="coffee">
export default
  name: 'SwrdCopyrightPrivacyInfoBlock'
</script>

<style lang="stylus" scoped>
a
  color #7790ab
  &:link
    text-decoration underline
p
  margin 0 auto
</style>
