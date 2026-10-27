# Ayu · Prism

**琥珀在素页上醒来，夜色里仍留一粒微光。让白昼，温柔地转入黄昏。**

[![发行附件下载量](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-ayu-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-ayu-prism/releases)

[English](README.md) · [下载 theme.json](https://github.com/EllisMorrow/tine-theme-ayu-prism/releases/latest/download/theme.json)

Ayu Light 与 Ayu Dark 汇成一套 Tine 主题：白日是清亮近白的留白，夜晚沉入深石墨色，并以暖橙、蓝绿点亮细节。

### 深色模式

![Ayu · Prism 深色模式实拍](docs/ayu-dark.png)

### 浅色模式

![Ayu · Prism 浅色模式实拍](docs/ayu-light.png)

*用户测试后提供的 Windows 实机截图，两套配色均实际包含在同一个主题包中。*

## 安装

1. 下载 [theme.json](https://github.com/EllisMorrow/tine-theme-ayu-prism/releases/latest/download/theme.json)。
2. 在 Tine 打开 **设置 → 外观 → 主题包 → 选择 theme.json**，选择下载的文件。
3. 点击 **使用颜色**，选择 **浅色、深色或跟随系统**。

需要主题 API **0.2** 支持。原有 `logseq/custom.css` 和设备强调色可能影响效果；主题只负责 API 支持的颜色，不包含额外字体、布局或任务标记样式。

## 配色

| 角色 | 浅色 | 深色 |
| --- | --- | --- |
| 主背景 | `#FCFCFC` | `#10141c` |
| 侧栏 | `#F3F4F5` | `#0A0E14` |
| 正文 | `#5C6166` | `#BFBDB6` |
| 标题 | `#404447` | `#E6E1CF` |
| 强调色 | `#FA8D3E` | `#FFB454` |
| 链接 | `#24668D` | `#59C2FF` |
| 标签 | `#5C7418` | `#AAD94C` |
| 高亮底色 | `#F8E6C6` | `#3E3627` |

## 验证情况

通过官方主题格式检查；浏览器样例检查了两套完整变量、模式切换及指定颜色组合。用户提供了上方 Windows 明暗实机截图，展示公开欢迎页面上的标题、正文、层级、链接、标签、行内代码和引用区域。高亮、选中操作、设置状态和其它平台未由这些截图覆盖，不据此宣称全部路径均已验证。

## 来源与边界

基于 [Ayu Light / Ayu Dark](https://github.com/ayu-theme/ayu-colors)，固定版本 `d461f02983546636bc6e1e0c48190fdb74036426`，采用 MIT 许可并保留 [原始声明](LICENSE)。Codex 中的 Ayu 参考为深色系列。Ayu 官方项目提供原生 Light、Dark、Mirage 变体；本包配对 Light 与 Dark，不声称 Ayu Light 是 Codex 原生预设，也未并入 Mirage。Tine 语义角色为独立映射。

独立社区适配由 EllisMorrow 完成，使用 AI 辅助开发。不分发 Codex 程序代码、标志或附带资源，不代表相关项目或 OpenAI 的官方产品，也不承诺与 Codex 像素级一致。具体映射和验证边界见 [适配说明](docs/adaptation.md)。

顶部徽标统计 GitHub Release 附件累计下载量，不代表安装人数。可在本仓库反馈问题，附版本、系统、模式及不包含私人内容的截图。

