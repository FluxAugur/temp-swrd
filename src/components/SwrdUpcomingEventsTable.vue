<template lang="pug">
#UpcomingEventsTable_wrapper.dataTables_wrapper.form-inline.dt-bootstrap.no-footer
  .row
    .col-sm-6
    .col-sm-6
  .row
    .col-sm-12
      table#UpcomingEventsTable.dt-responsive.nowrap.tableText.pull-right.hidden.dataTable.no-footer.dtr-inline(cellspacing='0' width='100%' frame='hsides' rules='thead , row=' role='grid' style='width: 100%;')
        thead
          tr(role='row')
            th.all.tableHeader.sorting_disabled(rowspan='1' colspan='1' style='width: 0px;')  Upcoming Events:
            th.all.purple-text.sorting_disabled(rowspan='1' colspan='1' style='width: 0px;') Dates:
            th.purple-text.sorting_disabled(data-priority='1' rowspan='1' colspan='1' style='width: 0px;') Hours of Operation:
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;') Street Address:
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;')
            th.purple-text.sorting_disabled(data-priority='1' rowspan='1' colspan='1' style='width: 0px;') County:
            th.purple-text.sorting_disabled(data-priority='1' rowspan='1' colspan='1' style='width: 0px;') City:
            th.purple-text.sorting_disabled(data-priority='1' rowspan='1' colspan='1' style='width: 0px;') State:
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;') Zip Code:
            th.purple-text.sorting_disabled(data-priority='1' rowspan='1' colspan='1' style='width: 0px;') Phone:
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;') Email:
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;') Website:
            th.purple-text.sorting_disabled(data-priority='1' rowspan='1' colspan='1' style='width: 0px;') Category
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;') Description:
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;') Comments:
            th.purple-text.sorting_disabled(data-priority='3' rowspan='1' colspan='1' style='width: 0px;') View Event:
        tbody
          tr.odd
            td.dataTables_empty(valign='top' colspan='16') No data available in table
  .row
    .col-sm-5
    .col-sm-7
</template>

<script lang="coffee">
export default
  name: 'SwrdUpcomingEventsTable'
</script>
