<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Joomla

[![集成程度](https://dash.yunohost.org/integration/joomla.svg)](https://ci-apps.yunohost.org/ci/apps/joomla/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/joomla.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/joomla.maintain.svg)

[![使用 YunoHost 安装 Joomla](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=joomla)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Joomla。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Joomla! is a free and open-source content management system (CMS) for publishing web content. Over the years Joomla! has won several awards. It is built on a model–view–controller web application framework that can be used independently of the CMS that allows you to build powerful online applications.


**分发版本：** 5.2.0~ynh2

## 截图

![Joomla 的截图](./doc/screenshots/screenshot.jpg)

## :red_circle: 负面特征

- **Package not maintained**: This YunoHost package is not actively maintained and needs adoption. This means that minimal maintenance is made by volunteers who don't use the app, so you should expect the app to lose reliability over time. You can [learn how to package](https://yunohost.org/packaging_apps_intro) if you'd like to adopt it.

## 文档与资源

- 官方应用网站： <https://www.joomla.org/>
- 官方管理文档： <https://docs.joomla.org/>
- 上游应用代码库： <https://github.com/joomla/joomla-cms>
- YunoHost 商店： <https://apps.yunohost.org/app/joomla>
- 报告 bug： <https://github.com/YunoHost-Apps/joomla_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/joomla_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/joomla_ynh/tree/testing --debug
或
sudo yunohost app upgrade joomla -u https://github.com/YunoHost-Apps/joomla_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
