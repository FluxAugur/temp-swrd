<template lang="pug">
nav.navbar.navbar-default.navbar-static-top
  .container
    .navbar-header
      // Collapsed Hamburger
      button.navbar-toggle.collapsed(type='button' data-toggle='collapse' data-target='#app-navbar-collapse')
        span.sr-only Toggle Navigation
        span.icon-bar
        span.icon-bar
        span.icon-bar
      // Branding Image
      a.navbar-brand(href='')
        img(src='../assets/images/header_logo_2014.png' style='width:190px;')
    #app-navbar-collapse.collapse.navbar-collapse
      // Left Side Of Navbar
      ul.nav.navbar-nav
        li
          a(href='events.html') Events
        li
          a(href='resources.html') Resources
        li
          a(href='worklist/generateReport') PDF Report
        li
          a(href='messageBoard') MB
        li
          a(href='fileupload') File Upload
        li
          a(href='contacts.html') Contacts
        li
          a(href='categories.html') Categories
        li
          a(href='flags.html')
            | Flags
            span#flagCount.badge.badge-danger
        li
          a(href='users.html') Users
        li
          a(href='archive') Archive
        li
          a(href='roles.html') Roles
      // Right Side Of Navbar
      ul.nav.navbar-nav.navbar-right
        // Authentication Links
        li.dropdown
          a.dropdown-toggle(href='#' data-toggle='dropdown' role='button' aria-expanded='false')
            | etc-dev
            span.caret
          ul.dropdown-menu(role='menu')
            li
              a(href='logout')
                i.fa.fa-btn.fa-sign-out
                | Logout
</template>

<script lang="coffee">
export default
  name: 'SwrdNav'
</script>

<style lang="stylus" scoped>
img
  width 190px

.badge-danger
  background-color #d9534f !important
  color white !important
  border-color #d43f3a !important

.fa-btn
  margin-right 6px

.icon-bar
  background-color #ffc72c !important

nav
  background-color #041e42
  height 70px

.navbar .nav > li > a
  color white
  vertical-align middle
  margin-top 10px

.navbar .nav > li > a:hover
  color #ffc72c

@media only screen and (max-width: 766px)
  .collapsing,
  .in
    background-color #ffc72c

  .collapsing ul li a,
  .in ul li a
    color #041e42 !important

  .collapsing ul li a:hover,
  .in ul li a:hover
    color #ffc72c !important
    background-color #041e42 !important
    box-shadow 0 6px #999

  .collapsing ul li a:active,
  .in ul li a:active
    color #ffc72c !important
    background-color #041e42 !important
    box-shadow 0 2px #666
    transform translateY(4px)

.navbar-toggle {
  background-color: #041e42 !important;
  vertical-align: middle;
  margin-top: 20px;
}
.navbar-toggle.collapsed {
  background-color: #041e42 !important;
}
.navbar-toggle.collapsed .icon-bar {
  background-color: #ffc72c !important;
}
.navbar-toggle:focus {
  background-color: #ffc72c !important;
}
.navbar-toggle.collapsed:focus {
  background-color: #041e42 !important;
}
.navbar-toggle.collapsed:focus .icon-bar {
  background-color: #ffc72c !important;
}
.navbar-toggle:focus .icon-bar {
  background-color: #041e42 !important;
}
@media (max-width: 1300px) {
  .navbar-header {
    float: none;
  }
  .collapsing,
  .in {
    background-color: #ffc72c;
  }
  .collapsing ul li a,
  .in ul li a {
    color: #041e42 !important;
  }
  .collapsing ul li a:hover,
  .in ul li a:hover {
    color: #ffc72c !important;
    background-color: #041e42 !important;
    box-shadow: 0 6px #999;
  }
  .collapsing ul li a:active,
  .in ul li a:active {
    color: #ffc72c !important;
    background-color: #041e42 !important;
    box-shadow: 0 2px #666;
    transform: translateY(4px);
  }
  .navbar-left,
  .navbar-right {
    float: none !important;
  }
  .navbar-toggle {
    display: block;
    background-color: #041e42 !important;
    vertical-align: middle;
    margin-top: 20px;
  }
  .navbar-collapse {
    border-top: 1px solid transparent;
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  }
  .navbar-fixed-top {
    top: 0;
    border-width: 0 0 1px;
  }
  .navbar-collapse.collapse {
    display: none !important;
  }
  .navbar-nav {
    float: none !important;
    margin-top: 7.5px;
  }
  .navbar-nav > li {
    float: none;
  }
  .navbar-nav > li > a {
    padding-top: 10px;
    padding-bottom: 10px;
  }
  .collapse.in {
    display: block !important;
  }
}
</style>
