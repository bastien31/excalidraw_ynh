# Excalidraw for YunoHost

[![Integration level](https://dash.yunohost.org/integration/excalidraw.svg)](https://dash.yunohost.org/appci/app/excalidraw) ![](https://ci-apps.yunohost.org/ci/badges/excalidraw.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/excalidraw.maintain.svg)  
[![Install Excalidraw with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=excalidraw)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install excalidraw quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
excalidraw is a real-time collaborative word processing web service. It uses Markdown language.

**Shipped version:** 1.6.0

## Screenshots

![](https://demo.excalidraw.org/screenshot.png)

## Demo

* [Official demo](https://excalidraw.com/)

## Configuration

You can configure excalidraw by editing this file `/var/www/excalidraw/config.json` using this the [documentation](https://github.com/excalidraw/server/blob/master/docs/configuration-config-file.md)

## Documentation

 * Official documentation: 
 * YunoHost documentation: 

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/excalidraw%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/excalidraw/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/excalidraw%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/excalidraw/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/codimd_ynh/issues
 * Upstream app repository: https://github.com/excalidraw/server/
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/excalidraw_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/codimd_ynh/tree/testing --debug
or
sudo yunohost app upgrade excalidraw -u https://github.com/YunoHost-Apps/excalidraw_ynh/tree/testing --debug
```
