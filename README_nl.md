<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Traggo voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/traggo.svg)](https://ci-apps.yunohost.org/ci/apps/traggo/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/traggo.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/traggo.maintain.svg)

[![Traggo met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Traggo snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Traggo is a tag-based time tracking tool.  
In Traggo there are no tasks, only tagged time spans.  
With tags, Traggo tries to be as customizable as possible, for example if you work on different projects you could add a project-tag.  
If you like to see statistics from the different things you do, you could add a type-tag with values like email, programming, meeting.  
You can do it just as you like.

### Features

- Easy to setup
- Time tracking (obviously)
- Customizable dashboards with diagrams
- A list and calendar view of the tracked time
- Sleek web ui with multiple themes
- Simple user management


**Geleverde versie:** 0.5.0~ynh1

## Schermafdrukken

![Schermafdrukken van Traggo](./doc/screenshots/traggo_calendar.png)

## Documentatie en bronnen

- Officiele website van de app: <https://traggo.net>
- Officiele beheerdersdocumentatie: <https://traggo.net/config/>
- Upstream app codedepot: <https://github.com/traggo/server>
- YunoHost-store: <https://apps.yunohost.org/app/traggo>
- Meld een bug: <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
of
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
