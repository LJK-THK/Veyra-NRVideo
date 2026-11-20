# Veyra 带鱼屏专用版 · Ultrawide Edition

这是 [Likely7/Veyra-NRVideo](https://github.com/Likely7/Veyra-NRVideo) 的社区分支。它为 21:9 带鱼屏播放 16:9 视频或显示采集画面时的左右留白添加可选背景，保留视频的原始比例。

[查看带鱼屏版源码（`ultrawide` 分支）](https://github.com/LJK-THK/Veyra-NRVideo/tree/ultrawide)

## 这次新增了什么

| 选项 | 效果 |
| --- | --- |
| 黑色 | 两侧显示黑色。 |
| 内置 | 从随附的 4 张原创 5:18 竖图中，分别为左右两侧选图。 |
| 自定义 | 从电脑上分别为左右两侧选择图片，支持 PNG、JPEG 和 BMP。 |
| 幻灯片（默认） | 每 20 秒从内置图库随机更换左右两张图。 |

背景亮度默认 **60%**，调到 **100%** 即为原图亮度。背景只在适应画面的宽屏预览和全屏有左右留白时显示。

## 怎么设置

打开带鱼屏版的 **设置 → 外观 → 两侧背景**。选「内置」或「自定义」后，点击左侧或右侧的小预览即可为对应一侧选图。

## 源码与致谢

带鱼屏功能源码位于 `ultrawide` 分支。Windows 构建可参考上游的[开发与构建文档](docs/DEVELOPMENT.md)。 [带鱼屏版源码](https://github.com/LJK-THK/Veyra-NRVideo/tree/ultrawide) · [提交给原作者的 PR #206](https://github.com/Likely7/Veyra-NRVideo/pull/206)

原项目由 **Likely7** 开发。感谢原作者和社区贡献者。 [上游项目与官方版本](https://github.com/Likely7/Veyra-NRVideo) · [GPL-3.0 许可](LICENSE) · [第三方声明](THIRD_PARTY_NOTICES.md)
