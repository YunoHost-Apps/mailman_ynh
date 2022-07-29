<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Mailman for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mailman.svg)](https://dash.yunohost.org/appci/app/mailman) ![Working status](https://ci-apps.yunohost.org/ci/badges/mailman.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/mailman.maintain.svg)  
[![Install Mailman with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mailman)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mailman quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Mailman is a (lightweight) free software for managing email discussion and e-newsletter lists. [Official website](http://www.list.org/)


**Shipped version:** 2.1.29-1~ynh3

## Screenshots

![Screenshot of Mailman](./doc/screenshots/screenshot.png)

## Disclaimers / important information

Mailman2 is a deprecated software : it relies on Python 2 which reached end of life in January 2020. Mailman 2 is not being developed anymore, and wont be available on Debian Bullseye / Yunohost 11.x. You should really consider using alternative solutions.

## Documentation and resources

* Official app website: <http://www.list.org/>
* Official admin documentation: <http://www.list.org/docs.html>
* Upstream app code repository: <https://code.launchpad.net/mailman>
* YunoHost documentation for this app: <https://yunohost.org/app_mailman>
* Report a bug: <https://github.com/YunoHost-Apps/mailman_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mailman_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/mailman_ynh/tree/testing --debug
or
sudo yunohost app upgrade mailman -u https://github.com/YunoHost-Apps/mailman_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
