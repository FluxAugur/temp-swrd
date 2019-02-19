<template lang="pug">
.swrd-pdf-report-button
  .col-xs-6.col-sm-6.col-md-4.col-lg-3
    a(href='worklist/generateReport')
      img.imglink(src='../assets/images/report-icon-2.png' alt='PDF Report')
    h3.footerlink
      a.long-link(href='worklist/generateReport') PDF Report
</template>

<script lang="coffee">
export default
  name: 'SwrdPdfReportButton'
</script>
