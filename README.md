<div align="center">

# Ayu · Prism

**Amber wakes on a pale page; a quiet ember waits beneath the night. Let the day turn gently into dusk.**

![Modes: light and dark](https://img.shields.io/badge/modes-light%20%2B%20dark-fa8d3e?labelColor=0f1419)
![Theme API: 0.2](https://img.shields.io/badge/Tine_theme_API-0.2-fa8d3e?labelColor=0f1419)
[![License: MIT](https://img.shields.io/badge/license-MIT-fa8d3e?labelColor=0f1419)](LICENSE)
[![Release downloads](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-ayu-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-ayu-prism/releases)

[Download theme.json](https://github.com/EllisMorrow/tine-theme-ayu-prism/releases/latest/download/theme.json) · [中文说明](README.zh-CN.md) · [Adaptation notes](docs/adaptation.md)

</div>

Ayu Light and Ayu Dark meet in one Tine theme: clean near-white space by day, deep charcoal by night, with warm orange and clear blue-green accents.

Explore the full [Prism theme gallery](https://github.com/martinkoutecky/tine/discussions/786) to compare all 29 themes in light and dark modes.

### Dark mode

![Ayu · Prism in Tine dark mode](docs/ayu-dark.png)

### Light mode

![Ayu · Prism in Tine light mode](docs/ayu-light.png)

*Actual Windows Tine screenshots supplied after testing. Both palettes are included in this package.*

## Install

1. Download [theme.json](https://github.com/EllisMorrow/tine-theme-ayu-prism/releases/latest/download/theme.json).
2. In Tine, open **Settings → Appearance → Theme packages → Select theme.json** and select the downloaded file.
3. Choose **Use colors**, then select **Light**, **Dark** or **System** mode.

Requires Tine Theme API **0.2** support. Existing `logseq/custom.css` and device accent settings may affect the result. This package supplies colors only; typography, layout, task markers and other roles outside the theme API remain host-controlled.

## Palette

| Role | Light | Dark |
| --- | --- | --- |
| Canvas | `#FCFCFC` | `#10141c` |
| Sidebar | `#F3F4F5` | `#0A0E14` |
| Body | `#5C6166` | `#BFBDB6` |
| Heading | `#404447` | `#E6E1CF` |
| Accent | `#FA8D3E` | `#FFB454` |
| Links | `#24668D` | `#59C2FF` |
| Tags | `#5C7418` | `#AAD94C` |
| Mark background | `#F8E6C6` | `#3E3627` |

## Tested in Tine

The manifest passed the official theme checker. A Chromium fixture checked both complete token sets, mode switching and specified contrast pairs. The user supplied the real Windows light/dark screenshots above using Tine's public welcome graph. The visible headings, body, outlines, links, tags, inline code and reference panels are shown; mark highlights, selection behavior, Settings and other platforms are not established by these images. See [screenshot notes](docs/screenshots.md).

## Source and scope

Based on [Ayu Light / Ayu Dark](https://github.com/ayu-theme/ayu-colors) at `d461f02983546636bc6e1e0c48190fdb74036426`, under MIT; see [LICENSE](LICENSE). The Codex reference is the dark Ayu family. The official Ayu project publishes native Light, Dark and Mirage variants; this package pairs Light and Dark without claiming Ayu Light is a Codex-native preset or including Mirage. Tine roles are mapped independently.

Independent community adaptation by **EllisMorrow**, developed with AI assistance (`aiDevelopment: primary`). No Codex program code, logo or bundled assets are included. No affiliation or endorsement is claimed.

Only the 21 supported literal color roles per mode are packaged. It does not claim pixel-for-pixel reproduction of Codex, or that all Tine-derived and opacity-dimmed text meets a contrast target. Check results and actual application coverage are recorded in [adaptation notes](docs/adaptation.md).

## Feedback

[Open an issue](https://github.com/EllisMorrow/tine-theme-ayu-prism/issues) with your Tine version, operating system, mode and a screenshot without private note content. The download badge counts GitHub Release asset downloads, not installations or unique users.

