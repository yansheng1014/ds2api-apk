# DS2API Android APK

DS2API Android 客户端 APK 发布仓库。

> **声明**：本仓库**仅发布 APK 构建产物，不含任何源码，项目不开源**。
> 请勿在本仓库提issues索要源码。

## 下载

到 [Releases](https://github.com/yansheng1014/ds2api-apk/releases) 页面下载最新 APK。

| 版本 | versionCode | 说明 |
|---|---|---|
| 3.9.0 | 8 | 对应上游 v3.9.0：修复正文中穿插思维链问题 |

## 系统要求

- Android 7.0+（minSdk 24）
- 仅支持 **arm64-v8a** 架构（主流 64 位手机均适用）

## 功能简介

- 在 Android 设备上本地运行 DS2API 服务端，提供 OpenAI / Claude / Gemini 兼容 API
- 内置 WebUI 管理界面（账号管理、API 测试、聊天记录、设置等）
- 内置 mihomo 内核（代理桥，安装后自动释放，无需手动下载）
- 服务通过前台服务保活，配合系统省电白名单使用效果更佳

## 使用提示

1. 安装后启动 App，服务监听 `http://127.0.0.1:5001`（管理界面 `/admin/`，API `/v1`）
2. 管理密钥显示在 App 主界面，首次使用请先添加账号
3. 如需代理桥功能，请在 WebUI 中配置订阅，mihomo 内核已随 APK 内置，无需手动下载

## 免责声明

本项目仅供个人学习与技术研究使用，使用者需自行承担使用风险。
