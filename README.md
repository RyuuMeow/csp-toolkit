# csp-toolkit

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-TW.md">繁體中文</a> |
  <a href="README.zh-CN.md">简体中文</a> |
  <a href="README.ja-JP.md">日本語</a>
</p>

A curated hub for utility tools that make Clip Studio Paint workflows faster, smoother, and easier to keep in rhythm.

This repository collects the CSP-related tools I build and maintain. Each tool lives in its own dedicated repository, while this repo acts as a lightweight directory with previews, descriptions, and links to installation details.

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
