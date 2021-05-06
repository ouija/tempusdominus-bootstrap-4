# Tempus Dominus Bootstrap 4 (𝖔𝖚𝖎𝖏𝖆 𝖒𝖔𝖉)
![GitHub version](https://badge.fury.io/gh/tempusdominus%2Fbootstrap-3-datetimepicker.png)

# 𝖔𝖚𝖎𝖏𝖆 𝖒𝖔𝖉𝖎𝖋𝖎𝖈𝖆𝖙𝖎𝖔𝖓𝖘
This fork contains bugfixes and patches that haven't yet been merged into the [original repository](https://github.com/tempusdominus/bootstrap-4) as of commit [#540bfae](https://github.com/tempusdominus/bootstrap-4/commit/540bfae18ca662bacfbea610e0ab8dcce6dd699e) (Oct 6, 2018), since the project appears to have possibly been abandoned.

Please consider [donating](https://paypal.me/djouija) to support this project. Thanks!

For further improved accessibility support, use [this branch](https://github.com/ouija/tempusdominus-bootstrap-4/tree/accessibility-fix)

Use either the minified or non-minified versions of both the css and js files found under the [build](https://github.com/ouija/tempusdominus-bootstrap-4/tree/master/build) folder.


Changelog:
* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/commit/58ddddaa1c7d7534af21f4fbc42180d48179d568) for [Issue #34](https://github.com/tempusdominus/bootstrap-4/issues/34) *(TypeError: Cannot read property 'isSame' of undefined error)*

* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/commit/d318c59ce191b9d09c71fc809e990afce17ec335) for [Issue #287](https://github.com/tempusdominus/bootstrap-4/issues/287) / [#159](https://github.com/tempusdominus/bootstrap-4/issues/159) *(Keybind events not working after date selection)*

* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/commit/623218e0a4318ea328a8ba764e1d76f30ecea558) for [Issue #139](https://github.com/tempusdominus/bootstrap-4/issues/139) / [Issue #88](https://github.com/tempusdominus/bootstrap-4/issues/80) *(allowInputToggle onclick toggle conflict)*

* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/commit/623218e0a4318ea328a8ba764e1d76f30ecea558) for [Issue #193](https://github.com/tempusdominus/bootstrap-4/issues/193) *(Cannot read property '_options' of undefined)*

* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/commit/ad5d26c88b404ad438c26eb6c5e2fbae2907b869) for [Issue #227](https://github.com/tempusdominus/bootstrap-4/issues/227) / [#95](https://github.com/tempusdominus/bootstrap-4/issues/95) / [#92](https://github.com/tempusdominus/bootstrap-4/issues/92) / [#42](https://github.com/tempusdominus/bootstrap-4/issues/42) *(fix events)*

* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/pull/1/commits/fa08722ce63424060fde48eeb818fdf1345e7f49) for [Issue #167](https://github.com/tempusdominus/bootstrap-4/issues/167) *(removing window.resize event listener)*

* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/commit/9215a556058fb45a9108d0264ce57c1f8a2201df) for [Issue #221](https://github.com/tempusdominus/bootstrap-4/issues/221) *(viewDate reset on hide when no selection is made)*

* Added [fix](https://github.com/ouija/tempusdominus-bootstrap-4/commit/f88ad2d74863a6762b8bd1577f558a198f84b783) for *active class to be applied to current, singular decade (when viewing date by decade)*

* Added fix for *screen reader 'blank' readout issue (by setting 'application' role attribute on targeted field)*

* Improved default keyBind methods - Added shift+arrow keys support, backspace to clear, space to select, and more.

