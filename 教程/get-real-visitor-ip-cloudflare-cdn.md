---
title: "Cloudflare CDN 环境下获取访客真实 IP 的配置指南"
date: 2022-01-18T17:50:12+00:00
url: https://www.resohub.net/2022/01/19/get-real-visitor-ip-cloudflare-cdn/
summary: "启用 Cloudflare CDN 后，服务器记录的 IP 往往是节点地址而非访客真实 IP。本文为你提供一套简单的 Nginx 配置代码，帮助你快速恢复真实 IP 记录，确保网站统计与安全防护的准确性。"
---

> **站点原文：** 完整内容、附件与更新请以 [阅读原文](https://www.resohub.net/2022/01/19/get-real-visitor-ip-cloudflare-cdn/) 为准。

## 文章看点

启用 Cloudflare CDN 后，服务器记录的 IP 往往是节点地址而非访客真实 IP。本文为你提供一套简单的 Nginx 配置代码，帮助你快速恢复真实 IP 记录，确保网站统计与安全防护的准确性。

## 内容预览

启用 Cloudflare CDN 后，源站接收到的所有请求均来自 Cloudflare 的节点地址。若要让服务器记录访客的真实 IP，需要对 Nginx 进行简单配置。 适用场景 本文以 宝塔面板 (BT Panel) 为例，适用于 Web 服务运行环境为 Nginx 的用户。 配置步骤 通过以下路径进入 Nginx 配置界面： 软件商店 $rightarrow$ 运行环境 $rightarrow$ 找到 Nginx 并点击 【设置】…

## 完整原文

请访问原文获取完整内容、资源链接与后续更新：[Cloudflare CDN 环境下获取访客真实 IP 的配置指南](https://www.resohub.net/2022/01/19/get-real-visitor-ip-cloudflare-cdn/)
