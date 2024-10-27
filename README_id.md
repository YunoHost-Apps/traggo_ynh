<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Traggo untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/traggo.svg)](https://ci-apps.yunohost.org/ci/apps/traggo/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/traggo.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/traggo.maintain.svg)

[![Pasang Traggo dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Traggo secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. With tags, Traggo tries to be as customizable as possible, for example if you work on different projects you could add a project-tag. If you like to see statistics from the different things you do, you could add a type-tag with values like email, programming, meeting.

### Features

- Easy to setup
- Time tracking (obviously)
- Customizable dashboards with diagrams
- A list and calendar view of the tracked time
- Sleek web ui with multiple themes
- Simple user management


**Versi terkirim:** 0.5.1~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Traggo](./doc/screenshots/traggo_calendar.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://traggo.net>
- Dokumentasi admin resmi: <https://traggo.net/config/>
- Depot kode aplikasi hulu: <https://github.com/traggo/server>
- Gudang YunoHost: <https://apps.yunohost.org/app/traggo>
- Laporkan bug: <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
atau
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
