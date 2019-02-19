<template lang="pug">
.swrd-etsu-contact-info-block
  p
    | East Tennessee State University
    br
    a(href='mailto:info@etsu.edu') info@etsu.edu
    br
    | PO Box 70300
    br
    | Johnson City, TN 37614
    br
    | 423-439-1000
</template>

<script lang="coffee">
export default
  name: 'SwrdEtsuContactInfoBlock'
</script>

<style lang="stylus" scoped>
  a
    color #7790ab
    &:link
      text-decoration underline
</style>
