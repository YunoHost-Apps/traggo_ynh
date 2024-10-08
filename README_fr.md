<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Traggo pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/traggo.svg)](https://ci-apps.yunohost.org/ci/apps/traggo/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/traggo.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/traggo.maintain.svg)

[![Installer Traggo avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Traggo rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Traggo est un outil de suivi du temps basé sur des balises. Dans Traggo, il n'y a pas de tâches, seulement des périodes de temps étiquetées. Avec les balises, Traggo essaie d'être aussi personnalisable que possible, par exemple si vous travaillez sur différents projets, vous pouvez ajouter une balise de projet.  
Si vous aimez voir des statistiques sur les différentes choses que vous faites, vous pouvez ajouter une balise de type avec des valeurs telles que e-mail, programmation, réunion.  

### Caractéristiques

- Facile à configurer
- Suivi du temps (évidemment)
- Tableaux de bord personnalisables avec diagrammes
- Une liste et une vue calendrier du temps suivi
- Interface utilisateur Web élégante avec plusieurs thèmes
- Gestion simple des utilisateurs


**Version incluse :** 0.5.0~ynh1

## Captures d’écran

![Capture d’écran de Traggo](./doc/screenshots/traggo_calendar.png)

## Documentations et ressources

- Site officiel de l’app : <https://traggo.net>
- Documentation officielle de l’admin : <https://traggo.net/config/>
- Dépôt de code officiel de l’app : <https://github.com/traggo/server>
- YunoHost Store : <https://apps.yunohost.org/app/traggo>
- Signaler un bug : <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
ou
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
