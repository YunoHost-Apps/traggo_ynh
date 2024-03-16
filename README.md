<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Traggo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/traggo.svg)](https://dash.yunohost.org/appci/app/traggo) ![Working status](https://ci-apps.yunohost.org/ci/badges/traggo.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/traggo.maintain.svg)

[![Install Traggo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Traggo quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. With tags, Traggo tries to be as customizable as possible, for example if you work on different projects you could add a project-tag. If you like to see statistics from the different things you do, you could add a type-tag with values like email, programming, meeting. You can do it just as you like.

### Features

- Easy to setup
- Time tracking (obviously)
- Customizable dashboards with diagrams
- A list and calendar view of the tracked time
- Sleek web ui with multiple themes
- Simple user management

**Shipped version:** 0.3.0~ynh2

## Screenshots

![Screenshot of Traggo](./doc/screenshots/traggo_calendar.png)

## Documentation and resources

- Official app website: <https://traggo.net>
- Official admin documentation: <https://traggo.net/config/>
- Upstream app code repository: <https://github.com/traggo/server>
- YunoHost Store: <https://apps.yunohost.org/app/traggo>
- Report a bug: <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing).

To try the testing branch, please proceed like that.

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
or
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
