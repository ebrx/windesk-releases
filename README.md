# WinDesk

WinDesk 是免费的 Windows 文件查找与整理工具。只记得文件用途时，可以直接描述它。要处理编号文件或杂乱目录，可以先核对名称和归档建议，再确认改动。

## 下载体验版

**WinDesk 0.19.1 Windows 开发预览版**。已验证的桌面环境为 Windows 11 x64。

- [下载 Windows x64 ZIP](https://github.com/ebrx/windesk-releases/releases/download/v0.19.1-preview/WinDesk-0.19.1-preview-windows-x64.zip) · [Release 更新记录](https://github.com/ebrx/windesk-releases/releases/tag/v0.19.1-preview) · [SHA-256 校验](https://github.com/ebrx/windesk-releases/releases/download/v0.19.1-preview/SHA256SUMS)
- [解压、更新与校验](INSTALLATION.md) · [免费激活](ACTIVATION.md) · [快速开始](GETTING-STARTED.md)

## 从这里开始

1. 退出旧版托盘进程，完整解压 ZIP，运行 `WinDesk.exe`。
2. 首次使用复制机器码，通过 [B 站私信](https://space.bilibili.com/481835793)或[邮件](mailto:ebrx@vip.qq.com)向作者免费领码，收到后粘贴激活。免费使用，无试用倒计时和订阅。
3. 在「文件库」加入一份目录副本。在「找文件」试着输入用途，例如「把旧环境资料搬到新环境」，对照命中原文和路径。
4. 要改名或归档，先查看预览。只勾选认可的建议，确认后再执行。已记录的操作可以按旧名找回，满足文件和目标条件时可以撤销。

## 搜索与本地模型

用途搜索随包提供，在本机建立索引，无需另装模型。可选的正文改名与分类建议需要自备本机 Ollama 和生成模型，或配置兼容 API。使用 API 时，软件在发送资料前单独请求授权。详见[模型配置](AI.md)与[隐私说明](PRIVACY.md)。

## 当前验证范围

这个版本适合先用模拟资料或文件副本试用。用途搜索只处理可提取文本，扫描件可先按名称查找。归档建议以所选根目录下的一级用途分类为范围。实测环境、操作边界和已知问题见[验证范围](TESTED.md)与[已知限制](KNOWN-LIMITATIONS.md)。

## 反馈

找不到、分错、改名不合适，欢迎通过 [GitHub Issues](https://github.com/ebrx/windesk-releases/issues)、[邮件](mailto:ebrx@vip.qq.com)或 [B 站私信](https://space.bilibili.com/481835793)反馈。请附应用版本、Windows 版本及脱敏复现步骤。

[常见问题](FAQ.md) · [更新记录](RELEASE-NOTES.md) · [当前包信息](downloads/latest.json) · [免费使用授权](FREEWARE-LICENSE.txt) · [第三方组件](THIRD-PARTY.md)
