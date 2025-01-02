<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Traggo dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/traggo)](https://ci-apps.yunohost.org/ci/apps/traggo/)
![Status działania](https://apps.yunohost.org/badge/state/traggo)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/traggo)

[![Zainstaluj Traggo z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Traggo na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. With tags, Traggo tries to be as customizable as possible, for example if you work on different projects you could add a project-tag. If you like to see statistics from the different things you do, you could add a type-tag with values like email, programming, meeting.

### Features

- Easy to setup
- Time tracking (obviously)
- Customizable dashboards with diagrams
- A list and calendar view of the tracked time
- Sleek web ui with multiple themes
- Simple user management


**Dostarczona wersja:** 0.6.1~ynh1

## Zrzuty ekranu

![Zrzut ekranu z Traggo](./doc/screenshots/traggo_calendar.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://traggo.net>
- Oficjalna dokumentacja dla administratora: <https://traggo.net/config/>
- Repozytorium z kodem źródłowym: <https://github.com/traggo/server>
- Sklep YunoHost: <https://apps.yunohost.org/app/traggo>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
lub
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
