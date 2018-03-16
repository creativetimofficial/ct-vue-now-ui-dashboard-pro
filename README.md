# [Vue Now UI Dashboard PRO](https://www.creative-tim.com/product/vue-now-ui-dashboard-pro) [![version][version-badge]][CHANGELOG]

![alt text](https://s3.amazonaws.com/creativetim_bucket/products/79/original/opt_nudp_vue_thumbnail.jpg?1521211107)

**[Vue Now UI Dashboard PRO](https://www.creative-tim.com/product/vue-now-ui-dashboard-pro)** is a beautiful resource built over Bootstrap and Vue.
It will help you get started developing dashboards in no time.

Vue Now UI Dashboard Pro is the Vue.js ported version of the [Original Now UI Dashboard Pro](https://www.creative-tim.com/product/now-ui-dashboard-pro).
Using the Dashboard is pretty simple but requires basic knowledge of Javascript, [Vue](https://vuejs.org/v2/guide/) and [Vue-Router](https://router.vuejs.org/en/).
Vue Paper Dashboard was coded by [Cristi Jora](https://github.com/cristijora) and the design was made by [Creative Tim](https://www.creative-tim.com/).
The product represents a big suite of front-end developer tools that can help you jump start your project. We have created it thinking about things you actually need in a dashboard. Vue Now UI Dashboard PRO contains handpicked and optimised Vuejs plugins. Everything is designed to fit with one another. As you will be able to see, the dashboard you can access on Creative Tim is a customisation of this product.

We like consistency and design that blends into its purpose.
Vue Now UI Dashboard PRO is a perfect example of our most thoughtful work. It combines Vue.js components and plugins, while looking like everything fits together.
For an easy start or inspiration for you project, we have also create a set of example pages, like the user settings or usage graphics.

It comes with 6 filter colors for the sidebar (“black”, “azure”,”green”,”orange”,”red”,”purple”) and an option to have a background image.

Let us know what you think and what we can improve below. And good luck with development!

## Links:

+ [Live Preview](http://vuejs.creative-tim.com/vue-now-ui-dashboard-pro)

## Quick Start:

Quick start options:

+ [Download from Creative Tim](https://www.creative-tim.com/product/vue-now-ui-dashboard-pro).
+ Make sure you have [Node js](https://nodejs.org/en/) installed
+ Go to the downloaded folder and open a terminal
+ Type `npm install` or `yarn install` if you use [yarn](https://yarnpkg.com/en/)
+ Type `npm run dev` to start a development server

The repo uses [vue-cli](https://github.com/vuejs/vue-cli) scaffolding which takes care of the development setup with webpack and all the necessary modern tools to make web development faster and easier.

Other Products:

+ [Download FREE Vue Version](https://www.creative-tim.com/product/vue-now-ui-dashboard).

### What's included

Within the download you'll find the following directories and files:
```
|-- src
    |-- App.vue
    |-- dashboard-plugin.js
    |-- globalComponents.js
    |-- globalDirectives.js
    |-- main.js
    |-- polyfills.js
    |-- assets
    |   |-- css
    |   |-- fonts
    |   |-- img
    |   |-- sass
    |       |-- element_variables.scss
    |       |-- now-ui-dashboard.scss
    |       |-- now-ui-dashboard
    |           |-- _alerts.scss
    |           |-- _badges.scss
    |           |-- _buttons.scss
    |           |-- _cards.scss
    |           |-- _carousel.scss
    |           |-- _checkboxes-radio.scss
    |           |-- _dropdown.scss
    |           |-- _example-pages.scss
    |           |-- _fixed-plugin.scss
    |           |-- _footers.scss
    |           |-- _images.scss
    |           |-- _info-areas.scss
    |           |-- _inputs.scss
    |           |-- _misc.scss
    |           |-- _mixins.scss
    |           |-- _modals.scss
    |           |-- _navbar.scss
    |           |-- _nucleo-outline.scss
    |           |-- _page-header.scss
    |           |-- _pagination.scss
    |           |-- _pills.scss
    |           |-- _popups.scss
    |           |-- _progress.scss
    |           |-- _responsive.scss
    |           |-- _sections.scss
    |           |-- _sidebar-and-main-panel.scss
    |           |-- _social-buttons.scss
    |           |-- _tables.scss
    |           |-- _tabs.scss
    |           |-- _timeline.scss
    |           |-- _typography.scss
    |           |-- _variables.scss
    |           |-- cards
    |           |   |-- _card-background.scss
    |           |   |-- _card-chart.scss
    |           |   |-- _card-collapse.scss
    |           |   |-- _card-contributions.scss
    |           |   |-- _card-info-area.scss
    |           |   |-- _card-lock.scss
    |           |   |-- _card-map.scss
    |           |   |-- _card-pricing.scss
    |           |   |-- _card-profile.scss
    |           |   |-- _card-signup.scss
    |           |   |-- _card-stats-mini.scss
    |           |   |-- _card-stats.scss
    |           |   |-- _card-subcategories.scss
    |           |   |-- _card-testimonials.scss
    |           |   |-- _card-wizard.scss
    |           |-- element-ui-plugins
    |           |   |-- _date_picker.scss
    |           |   |-- _input.scss
    |           |   |-- _select.scss
    |           |   |-- _tables.scss
    |           |   |-- _tags.scss
    |           |   |-- _tooltip.scss
    |           |-- mixins
    |           |   |-- _badges.scss
    |           |   |-- _buttons.scss
    |           |   |-- _cards.scss
    |           |   |-- _dropdown.scss
    |           |   |-- _inputs.scss
    |           |   |-- _modals.scss
    |           |   |-- _page-header.scss
    |           |   |-- _popovers.scss
    |           |   |-- _tags.scss
    |           |   |-- _transparency.scss
    |           |   |-- _vendor-prefixes.scss
    |           |   |-- _wizard.scss
    |           |-- plugins
    |               |-- _plugin-bootstrap-select.scss
    |               |-- _plugin-bootstrap-switch.scss
    |               |-- _plugin-card-wizard.scss
    |               |-- _plugin-fullcalendar.scss
    |               |-- _plugin-jquery.jvectormap.scss
    |               |-- _plugin-nouislider.scss
    |               |-- _plugin-perfect-scrollbar.scss
    |               |-- _plugin-sweetalert2.scss
    |-- components
    |   |-- AnimatedNumber.vue
    |   |-- Badge.vue
    |   |-- Button.vue
    |   |-- Dropdown.vue
    |   |-- LoadingPanel.vue
    |   |-- Modal.vue
    |   |-- Pagination.vue
    |   |-- Progress.vue
    |   |-- Slider.vue
    |   |-- Switch.vue
    |   |-- Table.vue
    |   |-- index.js
    |   |-- Breadcrumb
    |   |   |-- Breadcrumb.vue
    |   |   |-- BreadcrumbItem.vue
    |   |   |-- RouteBreadcrumb.vue
    |   |-- Cards
    |   |   |-- Card.vue
    |   |   |-- StatsCard.vue
    |   |-- Charts
    |   |   |-- BarChart.js
    |   |   |-- LineChart.js
    |   |   |-- utils.js
    |   |-- Collapse
    |   |   |-- Collapse.vue
    |   |   |-- CollapseItem.vue
    |   |-- Inputs
    |   |   |-- Checkbox.vue
    |   |   |-- IconCheckbox.vue
    |   |   |-- Radio.vue
    |   |   |-- formGroupInput.vue
    |   |-- Navbar
    |   |   |-- Navbar.vue
    |   |   |-- NavbarToggleButton.vue
    |   |-- NotificationPlugin
    |   |   |-- Notification.vue
    |   |   |-- Notifications.vue
    |   |   |-- index.js
    |   |-- Picker
    |   |   |-- DatePicker.vue
    |   |   |-- utils.js
    |   |-- SidebarPlugin
    |   |   |-- SideBar.vue
    |   |   |-- SidebarItem.vue
    |   |   |-- index.js
    |   |-- Tabs
    |   |   |-- Tab.vue
    |   |   |-- Tabs.vue
    |   |-- Timeline
    |   |   |-- TimeLine.vue
    |   |   |-- TimeLineItem.vue
    |   |-- Wizard
    |   |   |-- Wizard.vue
    |   |   |-- WizardTab.vue
    |   |   |-- throttle.js
    |   |-- WorldMap
    |       |-- AsyncWorldMap.vue
    |       |-- WorldMap.vue
    |       |-- world_map.js
    |-- pages
    |   |-- Dashboard
    |   |   |-- Charts.vue
    |   |   |-- DefaultHeader.vue
    |   |   |-- Widgets.vue
    |   |   |-- Calendar
    |   |   |   |-- Calendar.vue
    |   |   |   |-- CalendarHeader.vue
    |   |   |   |-- CalendarRoute.vue
    |   |   |-- Components
    |   |   |   |-- Buttons.vue
    |   |   |   |-- GridSystem.vue
    |   |   |   |-- Icons.vue
    |   |   |   |-- Notifications.vue
    |   |   |   |-- Panels.vue
    |   |   |   |-- SweetAlert.vue
    |   |   |   |-- Typography.vue
    |   |   |   |-- Headers
    |   |   |       |-- SweetAlertHeader.vue
    |   |   |-- Dashboard
    |   |   |   |-- Dashboard.vue
    |   |   |   |-- DashboardHeader.vue
    |   |   |   |-- HeaderChart.js
    |   |   |   |-- Stats
    |   |   |       |-- Task.vue
    |   |   |       |-- TaskList.vue
    |   |   |-- Forms
    |   |   |   |-- ExtendedForms.vue
    |   |   |   |-- RegularForms.vue
    |   |   |   |-- ValidationForms.vue
    |   |   |   |-- Wizard.vue
    |   |   |   |-- ValidationForms
    |   |   |   |   |-- LoginForm.vue
    |   |   |   |   |-- RangeValidationForm.vue
    |   |   |   |   |-- RegisterForm.vue
    |   |   |   |   |-- TypeValidationForm.vue
    |   |   |   |-- Wizard
    |   |   |       |-- FirstStep.vue
    |   |   |       |-- SecondStep.vue
    |   |   |       |-- ThirdStep.vue
    |   |   |-- Layout
    |   |   |   |-- Content.vue
    |   |   |   |-- ContentFooter.vue
    |   |   |   |-- DashboardLayout.vue
    |   |   |   |-- LoadingMainPanel.vue
    |   |   |   |-- TopNavbar.vue
    |   |   |   |-- Extra
    |   |   |       |-- MobileMenu.vue
    |   |   |       |-- UserMenu.vue
    |   |   |-- Maps
    |   |   |   |-- API_KEY.js
    |   |   |   |-- FullScreenMap.vue
    |   |   |   |-- GoogleMaps.vue
    |   |   |   |-- VectorMaps.vue
    |   |   |   |-- VectorMapsHeader.vue
    |   |   |   |-- WorldMap.vue
    |   |   |   |-- world_map.js
    |   |   |-- Pages
    |   |   |   |-- AuthLayout.vue
    |   |   |   |-- Lock.vue
    |   |   |   |-- Login.vue
    |   |   |   |-- Pricing.vue
    |   |   |   |-- Register.vue
    |   |   |   |-- TimeLinePage.vue
    |   |   |   |-- UserProfile.vue
    |   |   |   |-- background-2.jpg
    |   |   |   |-- UserProfile
    |   |   |       |-- EditProfileForm.vue
    |   |   |       |-- UserCard.vue
    |   |   |-- Tables
    |   |       |-- ExtendedTables.vue
    |   |       |-- PaginatedTables.vue
    |   |       |-- RegularTables.vue
    |   |       |-- users.js
    |   |       |-- ExtendedTables
    |   |           |-- ShoppingTable.vue
    |   |-- GeneralViews
    |       |-- NotFoundPage.vue
    |-- routes
        |-- routes.js
```

## Useful Links

More products from Creative Tim: <https://www.creative-tim.com/bootstrap-themes>

Tutorials: <https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w>

Freebies: <https://www.creative-tim.com/products>

Affiliate Program (earn money): <https://www.creative-tim.com/affiliates/new>

Social Media:

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>

[CHANGELOG]: ./CHANGELOG.md
[version-badge]: https://img.shields.io/badge/version-1.0.0-blue.svg
