# Pepettes pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/pepettes.svg)](https://dash.yunohost.org/appci/app/pepettes) ![](https://ci-apps.yunohost.org/ci/badges/pepettes.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/pepettes.maintain.svg)  
[![Installer Pepettes avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pepettes)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Pepettes rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Un simple formulaire de don avec stripe

**Version incluse :** 1.0.1~ynh2

**Démo :** https://donate.yunohost.org

## Avertissements / informations importantes

This app may be configured through the `settings.py` after installation.

## Documentations et ressources

* Documentation officielle de l'admin : https://github.com/YunoHost/pepettes/blob/main/README.md
* Dépôt de code officiel de l'app : https://github.com/YunoHost/pepettes/
* Documentation YunoHost pour cette app : https://yunohost.org/app_pepettes
* Signaler un bug : https://github.com/YunoHost-Apps/pepettes_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/pepettes_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/pepettes_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pepettes -u https://github.com/YunoHost-Apps/pepettes_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps