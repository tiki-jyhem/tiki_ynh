<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Tiki for YunoHost

[![Integration level](https://dash.yunohost.org/integration/tiki.svg)](https://dash.yunohost.org/appci/app/tiki) ![Working status](https://ci-apps.yunohost.org/ci/badges/tiki.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/tiki.maintain.svg)  
[![Install Tiki with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tiki)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Tiki quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Tiki Wiki CMS Groupware is the Free / Libre / Open Source Web Application with the most built-in features. Use cases: Web Publishing / Collaboration / Project Management / Office Suite / Knowledge base / Shopping Cart / Social Networking / CRM / Membership / E-learning. Tiki Trackers is the built-in database web apps builder and low-code / no-code application framework.


**Shipped version:** 24.2~ynh1

**Demo:** https://tiki.org/Try-Tiki

## Screenshots

![Screenshot of Tiki](./doc/screenshots/Screenshot.png)

## Disclaimers / important information

### Postinstall

Database credentials are sent by mail for the post installation. `http://example.org/tiki-install.php`

### Storing your uploaded files

To ease the install process and first access, Tiki saves your uploaded files (office documents, images, pdf, etc. attached to wiki pages, forum posts, tracker items, file galleries, ...) by default in its database. This works perfectly in most cases but it is not the recommended setup if you need to save many thousands of files or more.

In that case, consider switching from "Store to database" to "Store to directory", which you will find in the Configuration Wizard. Please use this preset path directory: `/home/yunohost.app/tiki`. You will be able to migrate your currently uploaded files from one to the other.
## Documentation and resources

* Official app website: <https://tiki.org/>
* Official admin documentation: <https://doc.tiki.org>
* Upstream app code repository: <https://gitlab.com/tikiwiki/tiki/>
* YunoHost documentation for this app: <https://yunohost.org/app_tiki>
* Report a bug: <https://github.com/YunoHost-Apps/tiki_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/tiki_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/tiki_ynh/tree/testing --debug
or
sudo yunohost app upgrade tiki -u https://github.com/YunoHost-Apps/tiki_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
