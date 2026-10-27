# Moon for Obsidian

[English](README.md) · 简体中文

一款向 Typora Moon 风格靠拢的 Obsidian 深色主题，搭配暖黄色强调色与细致的 Markdown 排版。

![Obsidian 中的 Moon 标题、行内格式和引用块](docs/screenshots/typography.png)

*使用主题预览笔记在 Obsidian 1.14.5 中实机截取。*

## 特点

- 深色写作背景、分级彩色标题竖线与黄色链接。
- 为引用块、表格、任务列表、Callout 和分割线设置样式。
- 带边框和语法高亮的代码块，以及 Mermaid 图表样式。
- 文件列表隐藏以 `.assets` 结尾的文件夹，笔记仍可使用其中的文件。
- 提供预览笔记，方便检查常见 Markdown 元素。

![Moon 主题中的 Java、Python 和 JavaScript 代码块](docs/screenshots/code.png)

## 安装

主题清单要求 Obsidian 1.4.0 或更新版本。截图采集于 Obsidian 1.14.5；不同版本和配置的渲染可能有所不同。

1. 下载或克隆本仓库。
2. 将整个 `Moon` 文件夹复制到笔记库的 `.obsidian/themes/` 下，确保 `theme.css` 和 `manifest.json` 位于 `.obsidian/themes/Moon/` 内。
3. 在 Obsidian 的 **设置 → 外观 → 主题**中选择 **Moon**，并使用深色模式。
4. 可将[预览笔记](docs/theme-preview.md)复制到自己的笔记库，打开后检查各项样式。

## 目录

```text
Moon/
  theme.css        主题样式
  manifest.json    Obsidian 主题信息
  fonts/           随主题提供的字体文件
docs/
  theme-preview.md  预览笔记
  screenshots/     Obsidian 实机截图
```

## 说明

- 本主题以视觉效果向 Typora Moon 靠拢；不同软件、字体、缩放比例和 Obsidian 版本不保证逐像素一致。
- CSS 保留了 Notation 2（Ha’ani Whitlock，基于 deathau 的 Notation）及 Typora Moon 的相关说明。第三方字体和主题素材可能适用各自的使用条款；本仓库目前未指定统一许可证。
- 可以修改 `Moon/theme.css` 来定制样式，并在 Obsidian 中重新加载或重新选择主题查看效果。
- 欢迎提交 Issue 和 PR。反馈显示问题时请附上 Obsidian 版本、操作系统和截图。
