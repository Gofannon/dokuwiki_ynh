<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Dokuwiki for YunoHost

[![Integration level](https://dash.yunohost.org/integration/dokuwiki.svg)](https://dash.yunohost.org/appci/app/dokuwiki) ![Working status](https://ci-apps.yunohost.org/ci/badges/dokuwiki.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/dokuwiki.maintain.svg)

[![Install Dokuwiki with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dokuwiki)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Dokuwiki quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

DokuWiki is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It is loved by users for its clean and readable syntax. The ease of maintenance, backup and integration makes it an administrator's favorite. Built in access controls and authentication connectors make DokuWiki especially useful in the enterprise context and the large number of plugins contributed by its vibrant community allow for a broad range of use cases beyond a traditional wiki.

## YunoHost specific features

* Integrate with YunoHost users and SSO - i.e. logout button
* Allow one user to be the "administrator" (set at the installation)
* Default authorization is set as read only so guest people cannot edit pages. (Especially needed if wiki is public to avoid spam and defacing. Can be changed from admin panel)
* During the upgrade, official plugins are also upgraded. We recommend that you should check that they run properly in the administration panel after the upgrade. We cannot know if some plugins are broken...


**Shipped version:** 2023.04.04a~ynh1

**Demo:** https://demo.yunohost.org/dokuwiki/doku.php?id=start&do=login&u=demo&p=demo

## Screenshots

![Screenshot of Dokuwiki](./doc/screenshots/DokuWiki_Screenshot.png)

## Documentation and resources

* Official app website: <https://www.dokuwiki.org>
* Official admin documentation: <https://www.dokuwiki.org/manual>
* Upstream app code repository: <https://github.com/dokuwiki/dokuwiki>
* YunoHost Store: <https://apps.yunohost.org/app/dokuwiki>
* Report a bug: <https://github.com/YunoHost-Apps/dokuwiki_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
or
sudo yunohost app upgrade dokuwiki -u https://github.com/YunoHost-Apps/dokuwiki_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
