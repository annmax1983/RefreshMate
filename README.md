# RefreshMate

English | [中文](languages/README_zh.md) | [日本語](languages/README_ja.md) | [Deutsch](languages/README_de.md) | [Español](languages/README_es.md) | [Français](languages/README_fr.md)

A lightweight browser extension for customizable auto page refresh with random intervals and keyword change alerts.

> Chromium-based · Manifest V3 · Minimal Permissions · Local Only

---

## Why RefreshMate?

Need to monitor a page for changes? RefreshMate auto-refreshes pages on your schedule and alerts you when keywords appear or disappear — perfect for stock monitoring, ticket sales, or any time-sensitive page.

| Advantage | Detail |
|-----------|--------|
| ⏱️ **Custom Intervals** | Quick presets (5s/30s/1min/5min) + custom input |
| 🎲 **Random Interval** | Anti-detection random range to avoid site blocks |
| 🔔 **Keyword Alerts** | Browser notifications when keywords appear/disappear |
| 🔒 **CAPTCHA Detection** | Auto-stops refresh when CAPTCHA is detected |
| 💾 **Per-Site Settings** | Each domain saves its own config independently |

---

## Features

| Feature | Description |
|---------|-------------|
| ⏱️ **Auto Refresh** | Set intervals from 5 seconds to hours |
| 🎲 **Random Range** | Set min/max range, interval randomized each cycle |
| 🧹 **Hard Refresh** | Bypass cache with Ctrl+Shift+R style reload |
| 🔔 **Keyword Monitor** | Alert when text appears or disappears on page |
| ⚠️ **CAPTCHA Stop** | Detects common CAPTCHA patterns, stops automatically |
| 🖼️ **Floating Overlay** | Mini countdown timer on the page |
| ⌨️ **Auto-Pause** | Pauses when typing in input fields |
| 💾 **Domain Memory** | Per-site settings saved automatically |

---

## Free vs Pro

| Capability | Free | Pro (License) |
|------------|------|----------------|
| 🗂️ **Simultaneous tabs** | **1 tab** at a time | ✅ Unlimited |
| 🎲 **Random interval range** | — | ✅ |
| 🔔 **Keyword / regex alerts** | — | ✅ |
| 🔄 **Any page change detection** | — | ✅ |
| 🆘 **Priority support** | — | ✅ |

The free version refreshes **only one tab at a time** across the whole browser. Upgrade to Pro to refresh multiple tabs simultaneously.

---

## Supported Browsers

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Fully supported |
| Microsoft Edge | ✅ Fully supported |
| Other Chromium-based | ✅ Should work |

---

## Installation

1. Clone or download this repository
2. Open `chrome://extensions/` (or `edge://extensions/`)
3. Enable **Developer mode**
4. Click **Load unpacked** → select the `RefreshMate` folder
5. Click the 🔄 RefreshMate icon to start

### Build

```bash
npm install
npm run build
```

---

## Privacy

- **activeTab** — Access current tab when you interact with the extension
- **tabs** — Find tabs to refresh by domain
- **storage** — Save settings locally
- **alarms** — Schedule refresh timers
- **notifications** — Browser notifications for keyword alerts
- **License validation** — anonymous device fingerprint + license key sent to `api.annmax1983.com` once every 24h. No browsing data transmitted.

**[📄 Privacy Policy](privacy-policy.html)**

---

## License

Copyright © 2026 RefreshMate. All rights reserved.

---

> **Note:** This repository is for **project showcase purposes only**.
