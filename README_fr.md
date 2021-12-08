# Syncthing pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/syncthing.svg)](https://dash.yunohost.org/appci/app/syncthing) ![](https://ci-apps.yunohost.org/ci/badges/syncthing.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/syncthing.maintain.svg)  
[![Installer Syncthing avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=syncthing)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Syncthing rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Syncthing is a continuous file synchronization program. It synchronizes files between two or more computers in real time, safely protected from prying eyes. Your data is your data alone and you deserve to choose where it is stored, whether it is shared with some third party, and how it's transmitted over the internet.


**Version incluse :** 1.18.5~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot1.png)

## Documentations et ressources

* Site officiel de l'app : https://syncthing.net
* Documentation officielle utilisateur : https://docs.syncthing.net
* Dépôt de code officiel de l'app : https://github.com/syncthing/syncthing
* Documentation YunoHost pour cette app : https://yunohost.org/app_syncthing
* Signaler un bug : https://github.com/YunoHost-Apps/syncthing_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing --debug
ou
sudo yunohost app upgrade syncthing -u https://github.com/YunoHost-Apps/syncthing_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps