# 安装与更新

> Public Beta v1.3.0-beta.1 已发布：[官方 Release](https://github.com/k-kaiko/KaikoLibrary/releases/tag/v1.3.0-beta.1)。

## 准备

- Windows 10/11 **64 位**；需要 .NET Framework 4.8 和 Microsoft Edge WebView2 Runtime。具体设备兼容性仍需公开 Beta 验收。
- 仅从本仓库的[官方 Releases](https://github.com/k-kaiko/KaikoLibrary/releases)取得安装包及 SHA-256 校验值。请核对 Release 中的安装包名称、大小和 SHA-256。
- 首次发布的安装包尚无可信发布者数字签名，Windows 可能显示“未知发布者”。无法确认文件来源时不要运行。

## 安装或覆盖升级

1. 关闭 KaikoLibrary；先备份原始图片，以及 `%LOCALAPPDATA%\KaikoLibrary\UserData`。不要把这些资料上传到 GitHub。
2. 下载官方安装包，并核对随 Release 公布的 SHA-256。
3. 自行运行安装包。隔离环境已验证从 V1.2.1、V1.3-P3、V1.3-P4 RC 覆盖升级；**无需先卸载，也不要删除 UserData**。其他旧版请先保留旧安装包，等待兼容性确认。
4. 打开软件，检查书库、收藏、标签和阅读进度。若书库授权提示要求确认目录，请选择原来的主目录；这不表示重新导入。

缺少 WebView2 Runtime 时，安装器会尝试使用微软引导程序，可能需要联网。如失败，可从[微软官方 WebView2 页面](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)取得 Runtime，再重试安装。

程序安装目录与个人数据目录分离，升级和卸载设计为保留个人数据。重要收藏仍应自行备份。发生问题时参见[常见问题](troubleshooting.md)，不要以清空数据作为常规修复方式。
