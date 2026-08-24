# DS2API Android APK

DS2API Android 客户端发布仓库（APK + 源码包）。

> **声明**：本仓库发布 APK 构建产物与源码压缩包，**源码可见但项目不开源**——
> 未授予任何开源许可证，保留所有权利。源码仅供学习参考，**禁止**再分发、
> 二次打包发布或用于其他商业用途。

## 下载

到 [Releases](https://github.com/yansheng1014/ds2api-apk/releases) 页面下载：

- `ds2api-android-vX.Y.Z.apk` — 安装包
- `ds2api-android-vX.Y.Z-source.zip` — 对应版本源码快照（不含签名密钥）

| 版本 | versionCode | 说明 |
|---|---|---|
| 4.0.0 | 9 | 对应上游 v4.0.0：工具调用兜底自动修复、跨协议翻译栈（OpenAI/Claude/Gemini）、TLS 指纹升级 |
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
