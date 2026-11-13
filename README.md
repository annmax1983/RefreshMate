# RefreshMate

English | [中文](languages/README_zh.md) | [日本語](languages/README_ja.md) | [Deutsch](languages/README_de.md) | [Español](languages/README_es.md) | [Français](languages/README_fr.md)

A lightweight browser extension for customizable auto page refresh, with optional Pro random intervals and keyword change alerts.

> Chrome · Edge · Firefox · Manifest V3 · Minimal Permissions · Local Only

Part of the [VKT](https://www.annmax1983.com/) privacy-first toolkit.

---

## Why RefreshMate?

Need to monitor a page for changes? RefreshMate auto-refreshes pages on your schedule. Pro adds alerts when keywords appear or disappear — perfect for stock monitoring, ticket sales, or any time-sensitive page.

| Advantage | Detail |
|-----------|--------|
| ⏱️ **Custom Intervals** | Quick presets (5s/30s/1min/5min) + custom input |
| 🎲 **Random Interval (Pro)** | Anti-detection random range to avoid site blocks |
| 🔔 **Keyword Alerts (Pro)** | Browser notifications when keywords appear/disappear |
| 🔒 **CAPTCHA Detection** | Auto-stops refresh when CAPTCHA is detected |
| 💾 **Per-Site Settings** | Each domain saves its own config independently |

---

## Features

| Feature | Description |
|---------|-------------|
| ⏱️ **Auto Refresh** | Set intervals from 5 seconds to hours |
| 🎲 **Random Range (Pro)** | Set min/max range, interval randomized each cycle |
| 🧹 **Hard Refresh** | Bypass cache with Ctrl+Shift+R style reload |
| 🔔 **Keyword Monitor (Pro)** | Alert when text appears or disappears on page |
| ⚠️ **CAPTCHA Stop** | Detects common CAPTCHA patterns, stops automatically |
| 🖼️ **Floating Overlay** | Mini countdown timer on the page — drag it anywhere, double-click to reset |
| ⌨️ **Auto-Pause** | Pauses when typing in input fields |
| 💾 **Domain Memory** | Per-site settings saved automatically |

---

## Free vs Pro

| Capability | Free | Pro (License) |
|------------|------|----------------|
| 🗂️ **Sites & tabs** | **1 site, 1 tab** at a time | ✅ Unlimited |
| 🎲 **Random interval range** | — | ✅ |
| 🔔 **Keyword / regex alerts** | — | ✅ |
| 🔄 **Any page change detection** | — | ✅ |

The free version monitors **one site at a time** and refreshes a single tab per site. Upgrade to Pro to refresh many sites and multiple tabs at once.

---

## Supported Browsers

| Browser | Status | Notes |
|---------|--------|-------|
| Google Chrome | ✅ Fully supported | Manifest V3 |
| Microsoft Edge | ✅ Fully supported | Manifest V3 |
| Mozilla Firefox | ✅ Fully supported | Manifest V3, Firefox 140+ (desktop) |
| Other Chromium-based | ✅ Should work | Manifest V3 |

> **Firefox note:** refresh timers, per-site settings, the overlay, CAPTCHA stop, auto-pause, Pro random intervals and keyword alerts all behave the same. Firefox has no `offscreen` document API, so the alert sound is played straight from the extension's background script via Web Audio, and the `offscreen` permission is not requested. Firefox asks only for `activeTab`, `tabs`, `storage`, `alarms`, `notifications`, `<all_urls>` (to draw the countdown overlay on pages) and the licence host.

---

## Installation

| Store | Link |
|---|---|
| Chrome Web Store | [Install for Chrome](https://chromewebstore.google.com/detail/camggpihgjdgbjnidhdalapchepdflbg) |
| Microsoft Edge Add-ons | [Install for Edge](https://microsoftedge.microsoft.com/addons/detail/ikgfdokioakgjgcmofboemcmahhnijjg) |
| Firefox Add-ons (AMO) | [Install for Firefox](https://addons.mozilla.org/firefox/addon/refreshmate-auto-refresh/) |

> Install only from the official stores above — avoid third-party download sites.

---

## Privacy

- **activeTab** — Access current tab when you interact with the extension
- **tabs** — Find tabs to refresh by domain
- **storage** — Save settings locally
- **alarms** — Schedule refresh timers (in-background timers handle intervals below 30s)
- **notifications** — Browser notifications for keyword alerts
- **offscreen** — Chrome / Edge only. Hidden document used only to play the alert sound; on Firefox the sound is played from the background script instead, so no such permission is needed
- **License validation** — anonymous install identifier + license key sent to `api.annmax1983.com` once every 2h. No browsing data transmitted.

**[📄 Privacy Policy](privacy-policy.html)**

---

## Source Code Notice

> ⚠️ **This repository is for project showcase only — the full source code is not published here.** It contains the user documentation, release notes and support information for the extension.

> 📥 **Download and install only from the official browser stores:** Chrome Web Store · Microsoft Edge Add-ons · Firefox Add-ons (AMO). No offline installation package is distributed from this repository.

---

## License

Copyright © 2026 RefreshMate. All rights reserved.

This software is proprietary and closed-source. Without prior written authorization from the author, decompiling, reverse-engineering, cracking, modifying, repackaging, redistributing or reselling the program (in whole or in part) is strictly prohibited.

---

## Links

- **Official website:** https://annmax1983.com/
- **This extension:** https://annmax1983.com/extensions/refreshmate
- **Privacy policy:** https://annmax1983.com/privacy
- **Contact:** support@annmax1983.com
- **☕ Support this project (Ko-fi):** https://ko-fi.com/annmax?ref=refreshmate
