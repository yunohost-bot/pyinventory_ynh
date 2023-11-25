<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# PyInventory for YunoHost

[![Integration level](https://dash.yunohost.org/integration/pyinventory.svg)](https://dash.yunohost.org/appci/app/pyinventory) ![Working status](https://ci-apps.yunohost.org/ci/badges/pyinventory.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/pyinventory.maintain.svg)

[![Install PyInventory with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pyinventory)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PyInventory quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

[![tests](https://github.com/YunoHost-Apps/pyinventory_ynh/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/YunoHost-Apps/pyinventory_ynh/actions/workflows/tests.yml)
[![codecov](https://codecov.io/github/jedie/pyinventory_ynh/branch/main/graph/badge.svg)](https://app.codecov.io/github/jedie/pyinventory_ynh)
[![pyinventory_ynh @ PyPi](https://img.shields.io/pypi/v/pyinventory_ynh?label=pyinventory_ynh%20%40%20PyPi)](https://pypi.org/project/pyinventory_ynh/)
[![Python Versions](https://img.shields.io/pypi/pyversions/pyinventory_ynh)](https://github.com/YunoHost-Apps/pyinventory_ynh/blob/main/pyproject.toml)
[![License GPL-3.0-or-later](https://img.shields.io/pypi/l/pyinventory_ynh)](https://github.com/YunoHost-Apps/pyinventory_ynh/blob/main/LICENSE)

[PyInventory](https://github.com/jedie/PyInventory) is a libre web-based management to catalog things including state and location etc. using [Python](https://www.python.org/)/[Django](https://www.djangoproject.com/).

Pull requests welcome ;)

This package for YunoHost used [django-yunohost-integration](https://github.com/YunoHost-Apps/django_yunohost_integration)

More screenshots are here: jedie.github.io/tree/master/screenshots/PyInventory


**Shipped version:** 0.19.3~ynh1

## Screenshots

![Screenshot of PyInventory](./doc/screenshots/pyinventory_v010_screenshot_2.png)
![Screenshot of PyInventory](./doc/screenshots/pyinventory_v010_screenshot_3.png)
![Screenshot of PyInventory](./doc/screenshots/pyinventory_v020_screenshot_1.png)
![Screenshot of PyInventory](./doc/screenshots/pyinventory_v0110_screenshot_memo_1.png)

## Documentation and resources

* Official user documentation: <https://github.com/jedie/PyInventory>
* Official admin documentation: <https://github.com/YunoHost-Apps/pyinventory_ynh>
* Upstream app code repository: <https://github.com/YunoHost-Apps/pyinventory_ynh>
* YunoHost Store: <https://apps.yunohost.org/app/pyinventory>
* Report a bug: <https://github.com/YunoHost-Apps/pyinventory_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/pyinventory_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/pyinventory_ynh/tree/testing --debug
or
sudo yunohost app upgrade pyinventory -u https://github.com/YunoHost-Apps/pyinventory_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
