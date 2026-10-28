# Mivra

[English](README.md) · [简体中文](README.zh-CN.md)

支持 macOS、Windows 和 Linux 的剪贴板、Markdown 便签、待办、书签、截图与翻译工作台。找回有用的片段，将便签留在眼前，从截图文字继续整理。功能与登录要求以所用版本及服务为准；在线服务需要网络，且可能有独立费用。

## 下载

只有官网下载页列为已发布的安装包可下载；其他平台和架构仍在准备中。

| 平台 | 已发布安装包 |
|---|---|
| macOS | [dmg Universal · Apple Silicon + Intel 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_universal.dmg) · [dmg Apple Silicon 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_arm64.dmg) |
| Windows | [exe x64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_x64.exe) · [msi x64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_x64.msi) · [exe ARM64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_arm64.exe) · [msi ARM64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_arm64.msi) |
| Linux | [AppImage x86_64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_x64.AppImage) · [deb x86_64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_x64.deb) · [AppImage ARM64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_arm64.AppImage) · [deb ARM64 1.0.0 (26072401)](https://github.com/zyravo-store/mivra/releases/download/v1.0.0/Mivra_1.0.0_26072401_arm64.deb) |

在[官网下载页](https://mivra.zyravo.store/download)选择操作系统与处理器，安装前阅读该版本发行说明。

[发行说明与安装包](https://github.com/zyravo-store/mivra/releases)

## 版本更新

在“设置 → 帮助”点击“检查更新”，读取官方公开 GitHub 仓库的稳定发行版。自动检查默认关闭，同时比较版本和 Build；Apple Silicon 选择 arm64 DMG，Intel 选择 Universal DMG。下载开始不代表安装完成，请退出应用后自行完成安装。

> **原先发布的 1.0.0 macOS 与 x64 安装包：**追加 ARM64 下载后，应用内检查更新目前会失败。请通过官网下载页查看版本并手动下载安装；现有安装包及公开校验值仍然有效。

## 开始使用

开启剪贴板采集，复制一小段公开示例文本，在剪贴板页面查看。搜索或收藏常用内容，整理便签、待办与书签，并在设置中配置快捷键。功能可用性以操作系统与实际发布的安装包为准。

[简体中文指南](https://github.com/zyravo-store/mivra/wiki/Home-zh-CN) · [English](https://github.com/zyravo-store/mivra/wiki/Home)。Wiki 单独发布。

## 备份与隐私

剪贴板 ZIP 与便签、待办、书签的工作区 JSON 是两份不同的备份，均未加密。请安全保管，恢复后核对内容，确认完整前保留原件。只开启需要的系统权限与第三方引擎。

通过 Homebrew 安装已发布的 macOS 包：

```sh
brew install --cask zyravo-store/mivra/mivra
```

官网：https://mivra.zyravo.store/ · 支持：support@zyravo.store

此公开仓库提供用户文档、问题反馈与发行下载；源码及开发历史单独维护。请勿在反馈中提交剪贴板正文、凭据、私人截图或原始诊断日志。
