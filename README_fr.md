# Metabase pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/metabase.svg)](https://dash.yunohost.org/appci/app/metabase) ![](https://ci-apps.yunohost.org/ci/badges/metabase.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/metabase.maintain.svg)  
[![Install Metabase with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=metabase)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Metabase rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Metabase is the easy, open source way for everyone in your company to ask questions and learn from data.

**Version incluse :** 0.40.1

## Captures d'écran

![](https://raw.githubusercontent.com/metabase/metabase/master/docs/metabase-product-screenshot.png)

## Démo

* [Démo officielle]()

## Guide d’installation

## Documentation

 * Documentation officielle : https://www.metabase.com/docs/latest/

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/metabase%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/metabase/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/metabase%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/metabase/)

## Limitations

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/metabase_ynh/issues
 * Site de l'application : https://metabase.com
 * Dépôt de l'application principale : https://github.com/metabase/metabase
 * Site web YunoHost : https://yunohost.org

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/metabase_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/metabase_ynh/tree/testing --debug
ou
sudo yunohost app upgrade metabase -u https://github.com/YunoHost-Apps/metabase_ynh/tree/testing --debug
```
