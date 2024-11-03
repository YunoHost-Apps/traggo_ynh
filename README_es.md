<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Traggo para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/traggo)](https://ci-apps.yunohost.org/ci/apps/traggo/)
![Estado funcional](https://apps.yunohost.org/badge/state/traggo)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/traggo)

[![Instalar Traggo con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarTraggo rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. With tags, Traggo tries to be as customizable as possible, for example if you work on different projects you could add a project-tag. If you like to see statistics from the different things you do, you could add a type-tag with values like email, programming, meeting.

### Features

- Easy to setup
- Time tracking (obviously)
- Customizable dashboards with diagrams
- A list and calendar view of the tracked time
- Sleek web ui with multiple themes
- Simple user management


**Versión actual:** 0.6.1~ynh1

## Capturas

![Captura de Traggo](./doc/screenshots/traggo_calendar.png)

## Documentaciones y recursos

- Sitio web oficial: <https://traggo.net>
- Documentación administrador oficial: <https://traggo.net/config/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/traggo/server>
- Catálogo YunoHost: <https://apps.yunohost.org/app/traggo>
- Reportar un error: <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
o
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
