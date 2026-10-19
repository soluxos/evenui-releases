# EvenUI

A design linter for the web. EvenUI loads any page, reads the computed styles of every visible element, works out the system the page is really using, and finds what doesn't fit: spacing off the scale, near-duplicate colours, font sizes between steps, one-off radii and shadows, components that drift from their siblings, text below WCAG contrast, and controls with no visible keyboard focus. Each issue is pinned to the page with the CSS file and line behind it.

**[evenui.com](https://evenui.com)** · [What it found on 41 product homepages](https://evenui.com/ui-consistency-report) · [Free palette checker](https://evenui.com/palette)

## Download

- Mac: [Apple silicon (M1 and later)](https://github.com/soluxos/evenui-releases/releases/latest/download/EvenUI-arm64.dmg) · [Intel](https://github.com/soluxos/evenui-releases/releases/latest/download/EvenUI-x64.dmg)
- Windows 10 and 11 (64-bit): [EvenUI-Setup.exe](https://github.com/soluxos/evenui-releases/releases/latest/download/EvenUI-Setup.exe)

Free to use: scan any page (a live site, a local dev server or an .html file), every check, design systems from a site, a repository or a tokens file, before and after comparisons, a CLI for CI, and an MCP server for Claude Code, Cursor and other MCP clients. [EvenUI Pro](https://evenui.com/#pricing) adds whole-site audits, watching a site on a schedule, stress tests and shareable reports, as a one-time payment. Every install has 14 days of Pro.

Installed copies update themselves: when a new version is out, EvenUI shows **Update available** in its sidebar.

> These builds aren't signed yet, so the first time you open EvenUI your computer asks you to confirm. On a Mac, open it once, then go to **System Settings → Privacy & Security** and choose **Open Anyway**. On Windows, if SmartScreen says it protected your PC, choose **More info → Run anyway**.

This repository holds release downloads only. What's new in each version is on the [releases page](https://github.com/soluxos/evenui-releases/releases).
