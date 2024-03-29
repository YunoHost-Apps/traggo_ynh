<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Traggo per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/traggo.svg)](https://dash.yunohost.org/appci/app/traggo) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/traggo.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/traggo.maintain.svg)

[![Installa Traggo con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Traggo su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. With tags, Traggo tries to be as customizable as possible, for example if you work on different projects you could add a project-tag. If you like to see statistics from the different things you do, you could add a type-tag with values like email, programming, meeting. You can do it just as you like.

### Features

- Easy to setup
- Time tracking (obviously)
- Customizable dashboards with diagrams
- A list and calendar view of the tracked time
- Sleek web ui with multiple themes
- Simple user management

**Versione pubblicata:** 0.3.0~ynh2

## Screenshot

![Screenshot di Traggo](./doc/screenshots/traggo_calendar.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://traggo.net>
- Documentazione ufficiale per gli amministratori: <https://traggo.net/config/>
- Repository upstream del codice dell’app: <https://github.com/traggo/server>
- Store di YunoHost: <https://apps.yunohost.org/app/traggo>
- Segnala un problema: <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
o
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
