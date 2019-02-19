<template lang="pug">
div#app
  swrd-nav
  .container(style="padding-left: 3px; padding-right: 3px;")
    .row
      .col-md-10.col-md-offset-1
        .padsome
          swrd-upcoming-events-table
        .panel-body.panel-primary.zeroTopMargin
          swrd-panel-heading
          swrd-panel-body
  swrd-footer
</template>

<script lang="coffee">
import SwrdFooter from '@/components/SwrdFooter'
import SwrdNav from '@/components/SwrdNav'
import SwrdPanelBody from '@/components/SwrdPanelBody'
import SwrdPanelHeading from '@/components/SwrdPanelHeading'
import SwrdUpcomingEventsTable from '@/components/SwrdUpcomingEventsTable'
export default
  name: 'app'
  components:
    'swrd-footer': SwrdFooter
    'swrd-nav': SwrdNav
    'swrd-panel-body': SwrdPanelBody
    'swrd-panel-heading': SwrdPanelHeading
    'swrd-upcoming-events-table': SwrdUpcomingEventsTable
</script>

<style lang="stylus">
#app
  font-family 'Lato'
  text-align center
  color #2c3e50

.imglink
  width 100%
  margin 0 auto
  margin-bottom 10px
  cursor pointer

.imglink2
  width 93%
  margin 0 auto
  margin-bottom 18px
  padding-left 10px
  cursor pointer

.long-link
  font-size 91%

.tableText
  margin-top 0px
  margin-bottom 0px
  margin 0 auto
  font-size 89%
  border 2px solid #041E42
  white-space nowrap

th, td
  padding-left 10px
  padding-bottom 8px
  padding-top 5px
  text-align left

.name
  table-layout fixed
  word-wrap break-word
  width 20%

.tableHeader
  margin 0 auto
  width 50%
  font-size 14px
  border-bottom 2px solid #041E42!important

th
  background-color #FFC72C!important
  color #041E42!important

.purple-btn
  background-color #041E42
  color white
  border 2px solid #FFC72C!important
  outline none
  white-space nowrap
  &:hover
    background-color #041E42
    color white
    border 2px solid #FFC72C!important
    outline none
  &:active
    background-color #041E42
    color white
    border 2px solid #FFC72C!important
    outline none
  &:focus
    background-color #041E42
    color white
    border 2px solid #FFC72C!important
    outline none

.orange
  background-color #FFC72C
  color #041E42
  border 2px solid #041E42!important
  font-weight bold
  &:hover
    background-color #FFC72C
    color #041E42
    border 2px solid #041E42!important
    font-weight bold
  &:active
    background-color #FFC72C
    color #041E42
    border 2px solid #041E42!important
    font-weight bold
  &:focus
    background-color #FFC72C
    color #041E42
    border 2px solid #041E42!important
    font-weight bold

.purple-text
  color #FFC72C!important
  border-bottom 2px solid #041E42!important

.view-btn
  margin-top 15px

.panel-primary
  border none!important
  background-color #ffffff!important

.zeroTopMargin
  margin-top 0px
  margin-bottom 0px

a:link, a:visited
  text-decoration none
  cursor auto
  margin-bottom 20px

a:link:active, a:visited:active
  text-decoration none
</style>
