<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Traggo

[![集成程度](https://dash.yunohost.org/integration/traggo.svg)](https://dash.yunohost.org/appci/app/traggo) ![工作状态](https://ci-apps.yunohost.org/ci/badges/traggo.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/traggo.maintain.svg)

[![使用 YunoHost 安装 Traggo](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=traggo)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Traggo。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 0.4.4~ynh1

## 截图

![Traggo 的截图](./doc/screenshots/traggo_calendar.png)

## 文档与资源

- 官方应用网站： <https://traggo.net>
- 官方管理文档： <https://traggo.net/config/>
- 上游应用代码库： <https://github.com/traggo/server>
- YunoHost 商店： <https://apps.yunohost.org/app/traggo>
- 报告 bug： <https://github.com/YunoHost-Apps/traggo_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/traggo_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
或
sudo yunohost app upgrade traggo -u https://github.com/YunoHost-Apps/traggo_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
