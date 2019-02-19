<template lang="pug">
.panel-body.w3-panel.w3-blue.w3-round-xlarge
  .row
    swrd-events-button
    swrd-resources-button
    swrd-pdf-report-button
    swrd-contacts-button
    swrd-categories-button
    swrd-flags-button
    swrd-users-button
    swrd-archive-button
</template>

<script lang="coffee">
import SwrdEventsButton from '@/components/SwrdEventsButton'
import SwrdResourcesButton from '@/components/SwrdResourcesButton'
import SwrdPdfReportButton from '@/components/SwrdPdfReportButton'
import SwrdContactsButton from '@/components/SwrdContactsButton'
import SwrdCategoriesButton from '@/components/SwrdCategoriesButton'
import SwrdFlagsButton from '@/components/SwrdFlagsButton'
import SwrdUsersButton from '@/components/SwrdUsersButton'
import SwrdArchiveButton from '@/components/SwrdArchiveButton'
export default
  name: 'SwrdPanelBody',
  components:
    'swrd-events-button': SwrdEventsButton
    'swrd-resources-button': SwrdResourcesButton
    'swrd-pdf-report-button': SwrdPdfReportButton
    'swrd-contact-button': SwrdContactsButton
    'swrd-categories-button': SwrdCategoriesButton
    'swrd-flags-button': SwrdFlagsButton
    'swrd-users-button': SwrdUsersButton
    'swrd-archive-button': SwrdArchiveButton
</script>

<style lang="stylus" scoped>
.panel-body
  border none!important
  background-color #ffffff !important

.panel-primary
  border-radius 15px
  border 3px solid #041e42 !important
  background-color #ffc72c !important
</style>
