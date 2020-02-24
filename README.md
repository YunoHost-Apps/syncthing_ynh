# Syncthing app for YunoHost

[![Integration level](https://dash.yunohost.org/integration/syncthing.svg)](https://dash.yunohost.org/appci/app/syncthing)  
[![Install Syncthing with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=syncthing)

> *This package allow you to install Syncthing quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Syncthing replaces proprietary sync and cloud services with something open, trustworthy and decentralized. Your data is your data alone and you deserve to choose where it is stored, if it is shared with some third party and how it's transmitted over the Internet.

**Shipped version:** 1.3.4

## Screenshots

![](https://docs.syncthing.net/_images/gs1.png)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: https://docs.syncthing.net

## YunoHost specific features

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/syncthing%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/syncthing/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/syncthing%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/syncthing/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/syncthing_ynh/issues
 * App website: https://syncthing.net/
 * Upstream app repository: https://github.com/syncthing/syncthing
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing --debug
or
sudo yunohost app upgrade syncthing -u https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing --debug
```
