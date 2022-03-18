# Joomla pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/joomla.svg)](https://dash.yunohost.org/appci/app/joomla) ![](https://ci-apps.yunohost.org/ci/badges/joomla.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/joomla.maintain.svg)  
[![Installer Joomla avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=joomla)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Joomla rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Joomla! is a free and open-source content management system (CMS) for publishing web content. Over the years Joomla! has won several awards. It is built on a model–view–controller web application framework that can be used independently of the CMS that allows you to build powerful online applications.


**Version incluse :** 4.1.0~ynh1



## Avertissements / informations importantes

# Ldap configuration (For now you have to configure it youeself)
Enable ldap Extension<br>
Enter the following feilds:<br>
**Host:** localhost<br>
**Port**:389<br>
**LdapV3:** Yes<br>
**Authorisation Method:** Bind and search<br>
**Base DN:** dc=yunohost,dc=org<br>
**uid:** uid=[search]<br>
**User's DN:** ou=users,dc=yunohost,dc=org<br>
**Map Full Name:** displayname<br>
**Map Email:** mail<br>
**Map User ID:** uid<br>

## Documentations et ressources

* Site officiel de l'app : https://www.joomla.org/
* Documentation officielle de l'admin : https://docs.joomla.org/
* Dépôt de code officiel de l'app : https://github.com/joomla/joomla-cms
* Documentation YunoHost pour cette app : https://yunohost.org/app_joomla
* Signaler un bug : https://github.com/YunoHost-Apps/joomla_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/joomla_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/joomla_ynh/tree/testing --debug
ou
sudo yunohost app upgrade joomla -u https://github.com/YunoHost-Apps/joomla_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps