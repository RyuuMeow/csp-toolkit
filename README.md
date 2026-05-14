# csp-toolkit

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.zh-CN.md">简体中文</a> |
  <a href="README.ja-JP.md">日本語</a>
</p>

A curated hub for Clip Studio Paint tools I develop, along with other interesting tools I have found that are made by other developers.

Each tool I develop lives in its own dedicated repository, while this repo acts as a lightweight directory with previews, descriptions, and links to installation details. I also keep a small list of other CSP tools I have found useful or interesting.

## Tools

### [GoPieMenu](https://github.com/RyuuMeow/GoPieMenu)

A cursor-centered pie menu that lets you collect many Clip Studio Paint shortcuts into one categorized, hierarchical menu. Instead of memorizing a large shortcut map, you only need one hotkey to open the menu and operate directly at the stylus tip.

Useful when you want to:

- Group lots of CSP tools, actions, and commands into clear categories.
- Build nested shortcut menus for large or specialized workflows.
- Trigger everything from one hotkey without moving your hand away from the drawing area.

<p align="center">
  <img src="demo/GoPieMenu_Demo.gif" alt="GoPieMenu demo">
</p>

---

### [ClipStudioPaint-Grayscale-Viewer](https://github.com/RyuuMeow/ClipStudioPaint-Grayscale-Viewer)

A non-intrusive grayscale preview overlay for Clip Studio Paint. It sits on top of the CSP app, so you do not need to open a separate preview window, and a single hotkey gives you a Photoshop-like grayscale preview experience.

Useful when you want to:

- Toggle grayscale preview while staying focused on the CSP canvas.
- Check values without modifying layers, color settings, or the working document.
- Avoid creating temporary color layers, filling them, and repeatedly toggling layers just to preview values.
- Get a familiar Photoshop-style grayscale preview flow inside CSP.

<p align="center">
  <img src="demo/ClipStudioPaint-Grayscale-Viewer_Demo.gif" alt="ClipStudioPaint-Grayscale-Viewer demo">
</p>

## Other CSP Tools I Found

Some useful or interesting Clip Studio Paint tools made by other creators.

> These projects are maintained by their respective authors. Please check each repository for installation details, compatibility notes, support, and license information.

- [ClipStudioPaint-Smooth-Color-Adjustment](https://github.com/MMmmmoko/ClipStudioPaint-Smooth-Color-Adjustment) - Improves CSP color adjustment and common blur preview responsiveness through CSP modification/plugin work, with extra workflow utilities such as timelapse export options.
- [clip_to_psd](https://github.com/dobrokot/clip_to_psd) - A Python script for converting Clip Studio Paint `.clip` files to PSD files.
- [CSPBrushExtract](https://github.com/MorrowShore/CSPBrushExtract) - Extracts parameters and brush tip bitmaps from Clip Studio Paint `.sut` brush files.
- [Brush-Converter](https://github.com/tohsakrat/Brush-Converter) - Scripts for unpacking material images and parameters from brush formats including Photoshop `.abr`, Procreate `.brushset`, and Clip Studio Paint `.sut`.

## Getting Started

1. Choose the tool you want from the list above.
2. Open its dedicated repository.
3. Download the latest release and follow that tool's setup instructions.

Because each project has its own behavior, requirements, and release cycle, installation and usage details are documented in the individual tool repositories.

## Repository Structure

```text
csp-toolkit/
├── demo/             # Preview GIFs used by this README
├── README.md         # English project index
├── README.zh-TW.md   # Traditional Chinese README
├── README.zh-CN.md   # Simplified Chinese README
└── README.ja-JP.md   # Japanese README
```

## Feedback

Bug reports, ideas, and workflow suggestions are welcome. For issues related to a specific tool, please open an issue in that tool's repository so the discussion stays close to the code.

## License

Each linked tool may use its own license. Please check the individual repository before reusing or redistributing code.
