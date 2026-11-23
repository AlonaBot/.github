<p align="center">
  <img src="https://raw.githubusercontent.com/AlonaBot/AlonaBot/main/docs/assets/mascot.png" alt="AlonaBot 吉祥物" width="180">
</p>

<h1 align="center">Hello AlonaBot 👋</h1>

<p align="center">
  轻量级、跨平台的 Go 聊天机器人框架。<br>
  按需安装组件，把机器人搭成你需要的样子。
</p>

<p align="center">
  <a href="https://alonabot.github.io/docs/">阅读文档</a> ·
  <a href="https://github.com/AlonaBot/AlonaBot/releases">下载 AlonaBot</a> ·
  <a href="https://github.com/AlonaBot/plugin-store">发现组件</a> ·
  <a href="https://github.com/AlonaBot/AlonaBot/discussions">交流讨论</a>
</p>

AlonaBot 用 Go 构建机器人的核心能力，通过 Adapter 连接聊天平台，通过插件扩展功能，通过 Agent 接入 AI，并提供 WebUI 集中管理配置、组件与运行状态。官方组件可以按需安装，也可以替换为社区或自己的实现。

独立进程部署让组件之间保持故障隔离；支持休眠的插件可以在空闲时退出，收到任务后自动唤醒。开发插件时，可直接使用命令与事件注册、SQLite 存储、配置表单、热重载和基于真实 Core 的测试套件，专注实现机器人的功能。

## 从这里开始

| 构建与使用 | 开发与扩展 |
| --- | --- |
| **[AlonaBot](https://github.com/AlonaBot/AlonaBot)**<br>框架核心、SDK 与管理 CLI | **[插件模板](https://github.com/AlonaBot/alonabot-plugin-template)**<br>从示例开始编写 Go 插件，检查并构建多平台发行物 |
| **[文档](https://alonabot.github.io/docs/)**<br>安装部署、配置与组件开发指南 | **[组件商店](https://github.com/AlonaBot/plugin-store)**<br>发现组件，提交自己的作品 |

## 官方组件

| 平台接入 | AI 与管理 |
| --- | --- |
| **[Telegram](https://github.com/AlonaBot/alonabot-adapter-telegram)**<br>连接 Telegram，处理消息与媒体 | **[Agent](https://github.com/AlonaBot/alonabot-agent)**<br>模型接入、会话与工具调用 |
| **[OneBot 11](https://github.com/AlonaBot/alonabot-adapter-onebot11)**<br>通过 OneBot 11 接入平台，当前支持接收 | **[WebUI](https://github.com/AlonaBot/alonabot-webui)**<br>管理配置、组件与运行状态 |

还有 **[Help 插件](https://github.com/AlonaBot/alonabot-plugin-help)**，提供命令列表与身份查询。

## 一起完善 AlonaBot

欢迎编写插件、接入更多平台、改善文档，或分享你的机器人用法。开发组件可以从 [插件开发指南](https://github.com/AlonaBot/AlonaBot/blob/main/docs/plugin-guide.zh-CN.md) 开始；参与框架开发请阅读 [贡献指南](https://github.com/AlonaBot/AlonaBot/blob/main/CONTRIBUTING.zh-CN.md)。

遇到问题？[提交 Issue](https://github.com/AlonaBot/AlonaBot/issues/new/choose)，附上版本、操作系统和复现步骤；有新想法，欢迎到 [Discussions](https://github.com/AlonaBot/AlonaBot/discussions) 聊聊。
