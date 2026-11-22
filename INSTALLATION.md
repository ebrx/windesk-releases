# 下载、解压与更新

[首页](README.md) · [免费激活](ACTIVATION.md) · [快速开始](GETTING-STARTED.md)

适用于 **WinDesk 0.19.1 Windows 开发预览版**。当前桌面验证环境为 Windows 11 x64。

1. 从 [0.19.1 Release](https://github.com/ebrx/windesk-releases/releases/tag/v0.19.1-preview)下载 [Windows x64 ZIP](https://github.com/ebrx/windesk-releases/releases/download/v0.19.1-preview/WinDesk-0.19.1-preview-windows-x64.zip) 和 [SHA256SUMS](https://github.com/ebrx/windesk-releases/releases/download/v0.19.1-preview/SHA256SUMS)。
2. 在 ZIP 所在目录打开 PowerShell，执行下面的命令。将结果与 `SHA256SUMS` 同名条目对照。
3. 从托盘退出旧版，将 ZIP 完整解压到独立目录，保留所有组件及 `semantic`、`licenses` 子目录。打开 `WinDesk.exe`，按[激活说明](ACTIVATION.md)完成首次免费激活。
4. 在文件库加入模拟资料或目录副本，再试找文件、预览、确认和撤销。

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\WinDesk-0.19.1-preview-windows-x64.zip'
```

准确大小和校验值见[当前包信息](downloads/latest.json)。

## 从旧版升级

保留旧程序目录和重要备份，逐步试用新版。保留原用户数据时通常可继续使用原激活、索引、收藏和恢复记录。需要领码或补领时，按[免费激活](ACTIVATION.md)操作。处理完待恢复批次后，再考虑清理程序或数据。
