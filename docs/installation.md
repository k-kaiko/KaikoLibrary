# 安装与覆盖升级

从 [v1.4.0 官方 Release](https://github.com/k-kaiko/KaikoLibrary/releases/tag/v1.4.0) 取得 `KaikoLibrary.v1.4.0.Setup.exe` 与 `SHA256SUMS.txt`。

## 安装前

- 面向 Windows 10/11 64 位，需要 .NET Framework 4.8 和 Microsoft Edge WebView2 Runtime。并非所有系统与硬件均已测试。
- 当前安装包没有可信发布者数字签名，Windows 可能提示“未知发布者”。请核对来源、文件名、大小和 SHA-256，无法确认来源时不要运行。
- 先关闭 KaikoLibrary，分别备份原始作品和 `%LOCALAPPDATA%\KaikoLibrary\UserData`；不要把备份传到 GitHub。

## 安装或更新

1. 核对 Release 中的 SHA-256 后，自行运行安装包，阅读并同意许可。
2. **不要先卸载旧版，不要清空 UserData。** 隔离测试覆盖 V1.2.1、V1.3-P3、V1.3-P4 RC、v1.3.0-beta.1、V1.4 candidate.1、candidate.2、rc.1 到本版。其他来源尚未逐一证明。
3. 打开应用，核对原书库、标签、收藏、分组和续读；若请求 Windows 原生授权，请选择原来的书库主目录。这不是重新导入。

缺少 WebView2 Runtime 时，安装器可使用微软引导程序获取 Runtime，可能需要联网。失败时从[微软官网](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)取得 Runtime 后重试。

安装文件与个人数据分离；覆盖升级、失败回滚及卸载保留用户数据的行为已用虚构配置验证，但不保证覆盖所有异常环境。保留旧安装包和备份；回退程序不等同于恢复个人数据库。请勿通过删除数据库或重装解决一般问题。参见[排障](troubleshooting.md)。
