<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Traggo YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/traggo)](https://ci-apps.yunohost.org/ci/apps/traggo/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/traggo)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/traggo)

[![Instalatu Traggo YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Traggo YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. With tags, Traggo tries to be as customizable as possible, for example if you work on different projects you could add a project-tag. If you like to see statistics from the different things you do, you could add a type-tag with values like email, programming, meeting.

### Features

- Easy to setup
- Time tracking (obviously)
- Customizable dashboards with diagrams
- A list and calendar view of the tracked time
- Sleek web ui with multiple themes
- Simple user management


**Paketatutako bertsioa:** 0.6.1~ynh1

## Pantaila-argazkiak

![Traggo(r)en pantaila-argazkia](./doc/screenshots/traggo_calendar.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://traggo.net>
- Administratzaileen dokumentazio ofiziala: <https://traggo.net/config/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/traggo/server>
- YunoHost Denda: <https://apps.yunohost.org/app/traggo>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
edo
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
