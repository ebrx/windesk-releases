# 安装、更新与校验

[首页](README.md) · [快速开始](GETTING-STARTED.md) · [免费激活](ACTIVATION.md) · [AI 与性能](AI.md) · [已知限制](KNOWN-LIMITATIONS.md) · [验证范围](TESTED.md)

**0.19.1 Windows 开发预览发布草稿，`published=false`。本文尚未公开，不代表新版已可下载。公开可用状态以[项目 Releases](https://github.com/ebrx/windesk-releases/releases)中的对应版本条目为准，既有公开版本及其记录保留。**

## 下载与校验

最终 ZIP 文件名、字节数、SHA-256 与实际下载 URL：`__PENDING__`。对应版本条目和附件尚未实际提供时，不将本稿视作已发布通知。稳定入口为[项目 Releases](https://github.com/ebrx/windesk-releases/releases)。

1. 下载对应版本的 Windows x64 完整 ZIP，核对发布页的外置 SHA-256 记录。
2. 从托盘退出旧版，将全部内容解压到独立目录，保留所有运行组件及 `semantic`、`licenses`。
3. 运行 `WinDesk.exe`，首次[免费激活](ACTIVATION.md)，先添加模拟资料或真实目录副本，试搜索、预览和有条件撤销。

可在 PowerShell 中运行，文件名由实际 Release 条目确定：

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\WinDesk-preview.zip'
```

上面只是命令示例，不是承诺的附件名。所得摘要必须与同一版本、同一文件名的外置校验记录一致。ZIP 自身摘要不写入随包文档，以发布页及校验附件为准。

## 更新与回退

更新通常保留原激活、索引、收藏和恢复记录；保留旧目录及重要备份，不要为清理环境删除用户数据。最终特定升级/回退场景未在本页宣称全面通过。删除程序目录不等于清掉全部本机缓存，先完成需要的恢复并保留日志。

用途搜索不要求额外 Python、数据库服务或 Ollama。可选生成能力另需自备模型或 API，并评估设备及明确发送授权。[快速开始](GETTING-STARTED.md) · [AI 与性能](AI.md)。
