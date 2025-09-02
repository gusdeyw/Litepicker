# Litepicker (Forked)

**This is a forked version of [wakirin/Litepicker](https://github.com/wakirin/Litepicker).**  
This fork is maintained by [gusdeyw](https://github.com/gusdeyw) and may include modifications and enhancements not present in the original repository.

## Recent Changes

- Added a 'Today' button to the calendar footer UI. When clicked, this button sets the date range to today (or today/tomorrow in range mode). Includes new logic, updated button text options and interfaces, and corresponding styles. ([commit 981c2ae](https://github.com/gusdeyw/Litepicker/commit/981c2ae971eb0a6ad2c6bb2704a73cef1fbb733d))

---

[![npm version](https://badge.fury.io/js/litepicker.svg)](https://www.npmjs.com/package/litepicker) [![Build Status](https://travis-ci.org/wakirin/Litepicker.svg?branch=master)](https://travis-ci.org/wakirin/Litepicker)

Litepicker
==========

Date range picker - lightweight, no dependencies

## Features
* No dependencies
* Single date or date range
* Show multiple months
* Min/Max days for select and/or Min/Max dates for select
* Select forward/backward
* Inline mode
* Repick date range
* Lock days  
* Keyboard accessibility (with plugin)
* Mobile friendly (with plugin)
* Predefined ranges (with plugin)
* Multiple select (with plugin)
  
See more details in docs.

# [Documentation](https://litepicker.com)

## Compatibility

##### Desktop
- IE 11 (required [polyfills](https://github.com/wakirin/litepicker-polyfills-ie11))
- Edge 17+
- Chrome 60+
- Firefox 52+
- Safari 10.1+
- Opera 48+

##### Mobile
- iOS 10+
  - Safari
  - Chrome
- Android 7+
  - Chrome
  - Firefox
  - Samsung Browser
  - UC Browser

## Plugins
* [keyboardnav](https://litepicker.com/docs/plugins/keyboardnav/) - adds keyboard navigation.
* [mobilefriendly](https://litepicker.com/docs/plugins/mobilefriendly/) - adds swipes (left/right) to switch months.
* [ranges](https://litepicker.com/docs/plugins/ranges/) - adds predefined ranges.
* [multiselect](https://litepicker.com/docs/plugins/multiselect/) - adds multiple selection.
