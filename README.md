# EAD Solution Pack

## Introduction

This repository contains the EAD solution pack. This module provides
functionality for ingestion and management of EADs.

## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)
* [Tuque](https://github.com/islandora/tuque)

In addition, [Bootstrap](https://getbootstrap.com/) and
[Popper.js](https://github.com/FezVrasta/popper.js) should be downloaded and
placed in sites/all/libraries:

* Bootstrap should be extracted into a libraries folder called 'bootstrap'
* `popper.min.js` should be placed in a libraries folder called 'popper.js'

All finding aids should have their namespace declared as `xmlns="urn:isbn:1-931666-22-9"`.

The module supports EAD 2002. It does not support EAD3.

## Installation

Install as usual, see
[this](https://drupal.org/documentation/install/modules-themes/modules-7) for
further information.

## Maintainers/Sponsors
Current maintainers:

* [Christopher Clement](https://github.com/Null-is-Null)

## License

[GPLv2](http://www.gnu.org/licenses/gpl-2.0.txt)
