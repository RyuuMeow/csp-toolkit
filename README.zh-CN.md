# csp-toolkit

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.zh-CN.md">简体中文</a> |
  <a href="README.ja-JP.md">日本語</a>
</p>

这是一个 Clip Studio Paint 工具集入口，整理我开发与维护的辅助工具，让绘图流程更快、更顺手，也更容易保持创作节奏。

每个工具都有独立的项目仓库；这个 repo 则作为轻量索引，集中放置工具简介、预览图与安装说明链接。我也会在这里整理一些自己发现、觉得有趣或实用的其他 CSP 工具。

## 工具列表

### [GoPieMenu](https://github.com/RyuuMeow/GoPieMenu)

一个以光标为中心的圆形菜单，可以把大量 Clip Studio Paint 快捷键集中到同一个 PieMenu 中，并支持分类与层级菜单。不需要再记住一整套复杂快捷键，只要一个快捷键，就能直接在笔尖附近完成操作。

适合用在：

- 将大量 CSP 工具、动作与命令整理成清晰分类。
- 为大型或专门流程建立层级式快捷菜单。
- 用单一快捷键调用所有常用操作，不必离开绘图区。

<p align="center">
  <img src="demo/GoPieMenu_Demo.gif" alt="GoPieMenu demo">
</p>

---

### [ClipStudioPaint-Grayscale-Viewer](https://github.com/RyuuMeow/ClipStudioPaint-Grayscale-Viewer)

一个不干扰工作流程的 Clip Studio Paint 灰阶预览覆盖工具。它会覆盖在 CSP app 上方，不需要另外开窗口预览；通过快捷键即可获得类似 Photoshop 的灰阶预览体验。

适合用在：

- 在不离开 CSP 画布的情况下切换灰阶预览。
- 不改动图层、色彩设置或工作文件，也能检查明度关系。
- 不必再建立临时颜色图层、铺底色，并反复开关图层来预览明度。
- 在 CSP 中获得接近 Photoshop 的灰阶预览流程。

<p align="center">
  <img src="demo/ClipStudioPaint-Grayscale-Viewer_Demo.gif" alt="ClipStudioPaint-Grayscale-Viewer demo">
</p>

## 我发现的其他 CSP 工具

一些由其他创作者制作、我觉得有用或有趣的 Clip Studio Paint 相关工具。

> 这些项目由各自的作者维护。安装方式、兼容性、支持与许可证信息，请以各项目仓库中的说明为准。

- [ClipStudioPaint-Smooth-Color-Adjustment](https://github.com/MMmmmoko/ClipStudioPaint-Smooth-Color-Adjustment) - 通过 CSP 修改与插件改善调色、常用模糊功能的预览流畅度，也提供缩时摄影导出选项等工作流程辅助功能。
- [clip_to_psd](https://github.com/dobrokot/clip_to_psd) - 将 Clip Studio Paint `.clip` 文件转换为 PSD 文件的 Python 脚本。
- [CSPBrushExtract](https://github.com/MorrowShore/CSPBrushExtract) - 从 Clip Studio Paint `.sut` 笔刷文件提取参数与笔尖位图。
- [Brush-Converter](https://github.com/tohsakrat/Brush-Converter) - 可从 Photoshop `.abr`、Procreate `.brushset`、Clip Studio Paint `.sut` 等笔刷格式中拆出素材图片与参数的脚本。

## 开始使用

1. 从上方工具列表选择想使用的工具。
2. 前往该工具的独立项目仓库。
3. 下载最新版本，并按照该项目的安装说明进行设置。

由于每个工具的功能、需求与发布节奏不同，详细安装与使用方式会放在各自的项目仓库中维护。

## 项目结构

```text
csp-toolkit/
├── demo/             # README 使用的预览 GIF
├── README.md         # English project index
├── README.zh-TW.md   # 繁體中文說明
├── README.zh-CN.md   # 简体中文说明
└── README.ja-JP.md   # 日本語说明
```

## 反馈

欢迎提供错误报告、功能想法或工作流程建议。如果问题与特定工具有关，请到该工具的项目仓库开 issue，方便让讨论与代码保持在同一个地方。

## 许可证

每个链接工具可能使用不同许可证。使用、修改或分发代码前，请先查看各工具仓库中的许可证信息。
