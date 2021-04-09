# Syncthing for YunoHost

[![Integration level](https://dash.yunohost.org/integration/syncthing.svg)](https://dash.yunohost.org/appci/app/syncthing) ![](https://ci-apps.yunohost.org/ci/badges/syncthing.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/syncthing.maintain.svg)  
[![Install Syncthing with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=syncthing)

> *This package allows you to install Syncthing quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Syncthing replaces proprietary sync and cloud services with something open, trustworthy and decentralized. Your data is your data alone and you deserve to choose where it is stored, if it is shared with some third party and how it's transmitted over the Internet.

**Shipped version:** 1.15.1

## Screenshots

![](https://docs.syncthing.net/_images/gs1.png)

## Documentation

 * Official documentation: https://docs.syncthing.net

## YunoHost specific features

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/syncthing%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/syncthing/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/syncthing%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/syncthing/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/syncthing_ynh/issues
 * App website: https://syncthing.net/
 * Upstream app repository: https://github.com/syncthing/syncthing
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing --debug
or
sudo yunohost app upgrade syncthing -u https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing --debug
```
