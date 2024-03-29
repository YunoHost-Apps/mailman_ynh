<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Mailman pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/mailman.svg)](https://dash.yunohost.org/appci/app/mailman) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/mailman.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/mailman.maintain.svg)  
[![Installer Mailman avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mailman)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Mailman rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Mailman est un logiciel libre (léger) pour la gestion de listes de discussion et de bulletins électroniques. [Site officiel](http://www.list.org/)


**Version incluse :** 2.1.29-1~ynh3

## Captures d'écran

![Capture d'écran de Mailman](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

Mailman2 est un logiciel déprécié : il repose sur Python 2 qui a atteint sa fin de vie en janvier 2020. Mailman 2 n'est plus développé, et ne sera pas disponible sur Debian Bullseye / Yunohost 11.x. Vous devriez vraiment envisager d'utiliser des solutions alternatives.
## Documentations et ressources

* Site officiel de l'app : <http://www.list.org/>
* Documentation officielle de l'admin : <http://www.list.org/docs.html>
* Dépôt de code officiel de l'app : <https://code.launchpad.net/mailman>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_mailman>
* Signaler un bug : <https://github.com/YunoHost-Apps/mailman_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mailman_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/mailman_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mailman -u https://github.com/YunoHost-Apps/mailman_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** <https://yunohost.org/packaging_apps>
