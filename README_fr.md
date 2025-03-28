<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Joomla pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/joomla)](https://ci-apps.yunohost.org/ci/apps/joomla/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/joomla)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/joomla)

[![Installer Joomla avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=joomla)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Joomla rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Joomla! est un système de gestion de contenu (CMS) gratuit et open source pour la publication de contenu Web. Au fil des années, Joomla! a remporté plusieurs prix. Il est construit sur un cadre d'application Web modèle-vue-contrôleur qui peut être utilisé indépendamment du CMS et qui vous permet de créer de puissantes applications en ligne.


**Version incluse :** 5.2.5~ynh1

## Captures d’écran

![Capture d’écran de Joomla](./doc/screenshots/screenshot.jpg)

## :red_circle: Anti-fonctionnalités

- **Package non maintenu **: Ce package YunoHost n'est pas activement maintenu et a besoin d'être adopté. Cela veut dire que la maintenance minimale est réalisée par des bénévoles qui n'utilisent pas l'application, il faut donc s'attendre à ce que l'app perde en fiabilité avec le temps. Vous pouvez [apprendre comment packager](https://yunohost.org/packaging_apps_intro) si vous voulez l'adopter.

## Documentations et ressources

- Site officiel de l’app : <https://www.joomla.org/>
- Documentation officielle de l’admin : <https://docs.joomla.org/>
- Dépôt de code officiel de l’app : <https://github.com/joomla/joomla-cms>
- YunoHost Store : <https://apps.yunohost.org/app/joomla>
- Signaler un bug : <https://github.com/YunoHost-Apps/joomla_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/joomla_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/joomla_ynh/tree/testing --debug
ou
sudo yunohost app upgrade joomla -u https://github.com/YunoHost-Apps/joomla_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
