# Veyra 2.2.0 带鱼屏专用版 · Ultrawide Edition

这个社区版基于 [Likely7 的 Veyra 2.2.0](https://github.com/Likely7/Veyra-NRVideo/releases/tag/v2.2.0)，为带鱼屏播放 16:9 视频或显示采集画面时的左右留白添加背景。

[查看 2.2.0 带鱼屏源码](https://github.com/LJK-THK/Veyra-NRVideo/tree/ultrawide-2.2.0)

## 带鱼屏功能

| 选项 | 效果 |
| --- | --- |
| 黑色 | 两侧显示黑色。 |
| 内置 | 从 4 张原创竖图中分别为左右选图。 |
| 自定义 | 从电脑上独立选择左右图片，支持 PNG、JPEG 和 BMP。 |
| 幻灯片（默认） | 每 20 秒随机更换左右两张竖图。 |

打开 **设置 → 外观 → 两侧背景**。可把背景亮度从默认的 **60%** 调到 **100%** 原图亮度。背景随实际左右留白显示，视频按所选比例呈现。

## 2.2.0 使用方法

公开补丁适用于官方 **NVIDIA Windows x64 2.2.0 常规便携版**。把补丁里 `copy-into-Veyra` 的内容复制到 `Veyra.exe` 所在目录，合并 `versions` 文件夹后运行 `Veyra.exe`。

[查看 Releases](https://github.com/LJK-THK/Veyra-NRVideo/releases) · [官方 2.2.0 基础包](https://github.com/Likely7/Veyra-NRVideo/releases/tag/v2.2.0)

## 源码与致谢

2.2.0 带鱼屏源码位于 `ultrawide-2.2.0` 分支。带鱼屏功能最初通过 [PR #206](https://github.com/Likely7/Veyra-NRVideo/pull/206) 提交给原作者。感谢 **Likely7** 和 Veyra 社区贡献者。

[GPL-3.0](LICENSE) · [第三方声明](THIRD_PARTY_NOTICES.md) · [开发与构建文档](docs/DEVELOPMENT.md)
