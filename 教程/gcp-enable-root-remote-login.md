---
title: "Google Cloud Platform (GCP) 实例启用 root 用户远程登录指南"
date: 2021-12-16T21:14:15+00:00
url: https://www.resohub.net/2021/12/17/gcp-enable-root-remote-login/
summary: "想摆脱谷歌云默认禁用的 root 登录限制？本文为你提供一套简单直接的配置步骤，助你快速开启 root 远程访问权限。只需跟随指南操作，即可实现高效管理服务器，且该方法同样适用于大多数 Linux 云环境。"
---

> **站点原文：** 完整内容、附件与更新请以 [阅读原文](https://www.resohub.net/2021/12/17/gcp-enable-root-remote-login/) 为准。

## 文章看点

想摆脱谷歌云默认禁用的 root 登录限制？本文为你提供一套简单直接的配置步骤，助你快速开启 root 远程访问权限。只需跟随指南操作，即可实现高效管理服务器，且该方法同样适用于大多数 Linux 云环境。

## 内容预览

谷歌云服务器开启 root 远程登录教程 谷歌云（GCP）实例在创建后，默认处于禁用 root 账户登录状态。若需开启 root 远程访问，可参考以下步骤操作。此方法同样适用于大多数基于 Linux 的云服务器环境。 第一步：进入 SSH 终端 在谷歌云控制台的实例详情页面，点击 SSH 按钮，通过网页版终端进入服务器内部。 第二步：配置 root 用户密码 由于 root 账户初始无密码，需先为其设置登录凭据： 执行命令：sudo p…

## 完整原文

请访问原文获取完整内容、资源链接与后续更新：[Google Cloud Platform (GCP) 实例启用 root 用户远程登录指南](https://www.resohub.net/2021/12/17/gcp-enable-root-remote-login/)
