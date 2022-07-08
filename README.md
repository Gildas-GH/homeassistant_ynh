<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Home Assistant for YunoHost

[![Integration level](https://dash.yunohost.org/integration/homeassistant.svg)](https://dash.yunohost.org/appci/app/homeassistant) ![Working status](https://ci-apps.yunohost.org/ci/badges/homeassistant.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/homeassistant.maintain.svg)  
[![Install Home Assistant with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=homeassistant)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Home Assistant quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Home automation platform

**Shipped version:** 2022.7.0~ynh1

**Demo:** https://demo.home-assistant.io

## Screenshots

![Screenshot of Home Assistant](./doc/screenshots/screenshot1)

## Disclaimers / important information

* Known limitations:
    * Are LDAP and HTTP auth supported? LDAP=Yes | HTTP auth=No
    * Can the app be used by multiple users? Yes


* Additional informations:
    * As the pyhton version shipped in Debian stable is not always supported, a recent version could be built during the installation process. It may take a while to achive that (15 to 60 minutes)

## Documentation and resources

* Official app website: <https://www.home-assistant.io>
* Official admin documentation: <https://www.home-assistant.io/docs/>
* Upstream app code repository: <https://github.com/home-assistant/core>
* YunoHost documentation for this app: <https://yunohost.org/app_homeassistant>
* Report a bug: <https://github.com/YunoHost-Apps/homeassistant_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/homeassistant_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/homeassistant_ynh/tree/testing --debug
or
sudo yunohost app upgrade homeassistant -u https://github.com/YunoHost-Apps/homeassistant_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
