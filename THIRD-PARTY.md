# 第三方组件与许可

[返回 WinDesk 首页](README.md)

WinDesk 按[免费使用授权](FREEWARE-LICENSE.txt)提供，主程序源码保持私有，未指定开源许可证。免费激活不等于授予源代码、品牌或第三方材料的再许可。

| 组件 | 用途 | 来源与许可 |
| --- | --- | --- |
| SQLite 3.54.0 | 本地索引及操作日志 | [SQLite 版权说明](https://www.sqlite.org/copyright.html)，公有领域；包内 `licenses/sqlite.md` |
| BAAI BGE base 中文 v1.5 | 本地语义检索 | [原模型](https://huggingface.co/BAAI/bge-base-zh-v1.5)及 [Xenova ONNX 转换](https://huggingface.co/Xenova/bge-base-zh-v1.5)，MIT；包内 `semantic/BGE-LICENSE.txt` |
| Microsoft ONNX Runtime 1.31.0 | CPU 推理 | [官方仓库](https://github.com/microsoft/onnxruntime)，MIT 及第三方通知；包内 `semantic/ONNXRUNTIME-LICENSE.txt`、`semantic/ONNXRUNTIME-NOTICES.txt` |
| Microsoft Fluent System Icons | 部分应用操作图标 | [官方仓库](https://github.com/microsoft/fluentui-system-icons)，MIT；包内 `THIRD_PARTY.md` 保留许可 |
| Microsoft Visual C++ Runtime | 运行时支持 | 按 Microsoft 可再分发条款提供原样 DLL；见包内第三方说明 |

可选 GPU 组件使用 Windows 自带的 Windows.AI.MachineLearning / DirectX 接口，不捆绑 CUDA 或显卡驱动。模型没有为 WinDesk 重新训练，组件作者不为检索或分类结果背书。

具体版本、模型指纹和完整通知以对应软件包中的 `THIRD_PARTY.md` 及许可文件为准；更新时请连同这些文件保留。
