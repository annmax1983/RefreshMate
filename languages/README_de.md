# RefreshMate
[English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | Deutsch | [Español](README_es.md) | [Français](README_fr.md)

Eine leichte Browser-Erweiterung für automatisches Aktualisieren von Seiten mit konfigurierbaren Intervallen und Benachrichtigungen bei Keyword-Änderungen.

> Chromium-basiert · Manifest V3 · Minimale Berechtigungen · Lokal

---

## Warum RefreshMate?

Müssen Sie eine Seite auf Änderungen überwachen? RefreshMate aktualisiert Seiten automatisch nach Ihrem Zeitplan und benachrichtigt Sie, wenn Keywords erscheinen oder verschwinden — perfekt für Aktienbeobachtung, Ticketverkäufe oder jede zeitkritische Seite.

| Vorteil | Detail |
|---------|--------|
| ⏱️ **Benutzerdefinierte Intervalle** | Schnell-Presets (5s/30s/1min/5min) + eigener Wert |
| 🎲 **Zufälliges Intervall** | Zufallsbereich gegen Erkennung, um Blockaden zu vermeiden |
| 🔔 **Keyword-Benachrichtigungen** | Browser-Benachrichtigungen bei Erscheinen/Verschwinden |
| 🔒 **CAPTCHA-Erkennung** | Stoppt die Aktualisierung bei CAPTCHA automatisch |
| 💾 **Pro-Site-Einstellungen** | Jede Domain speichert ihre Konfiguration unabhängig |

---

## Funktionen

| Funktion | Beschreibung |
|----------|--------------|
| ⏱️ **Automatisches Aktualisieren** | Intervalle von 5 Sekunden bis Stunden |
| 🎲 **Zufallsbereich** | Min./Max.-Bereich, Intervall wird je Zyklus zufällig |
| 🧹 **Erneuern** | Cache umgehen (Ctrl+Shift+R Stil) |
| 🔔 **Keyword-Überwachung** | Benachrichtigung bei Erscheinen/Verschwinden von Text |
| ⚠️ **CAPTCHA-Stopp** | Erkennt häufige CAPTCHA-Muster, stoppt automatisch |
| 🖼️ **Schwebender Overlay** | Mini-Countdown-Timer auf der Seite |
| ⌨️ **Auto-Pause** | Pausiert beim Tippen in Eingabefeldern |
| 💾 **Domain-Speicherung** | Pro-Site-Einstellungen werden automatisch gespeichert |

---

## Kostenlos vs. Pro

| Funktion | Kostenlos | Pro (Lizenz) |
|----------|-----------|--------------|
| 🗂️ **Gleichzeitig aktualisierte Tabs** | **Nur 1 Tab** gleichzeitig | ✅ Unbegrenzt |
| 🎲 **Zufälliger Intervallbereich** | — | ✅ |
| 🔔 **Keyword-/Regex-Alarme** | — | ✅ |
| 🔄 **Erkennung beliebiger Seitenänderungen** | — | ✅ |
| 🆘 **Priorisierter Support** | — | ✅ |

Die kostenlose Version aktualisiert im gesamten Browser **immer nur einen Tab gleichzeitig**. Mit Pro können mehrere Tabs gleichzeitig aktualisiert werden.

---

## Unterstützte Browser

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Voll unterstützt |
| Microsoft Edge | ✅ Voll unterstützt |
| Andere Chromium-basiert | ✅ Sollte funktionieren |

---

## Installation

1. Dieses Repository klonen oder herunterladen
2. `chrome://extensions/` (oder `edge://extensions/`) öffnen
3. **Entwicklermodus** aktivieren
4. **Entpackte Erweiterung laden** → `RefreshMate`-Ordner auswählen
5. Auf das 🔄 RefreshMate-Symbol klicken, um zu starten

### Build

```bash
npm install
npm run build
```

---

## Datenschutz

- **activeTab** — Zugriff auf den aktuellen Tab bei Interaktion
- **tabs** — Tabs zum Aktualisieren per Domain finden
- **storage** — Einstellungen lokal speichern
- **alarms** — Aktualisierungs-Timer planen
- **notifications** — Browser-Benachrichtigungen für Keyword-Alarme
- **Lizenzvalidierung** — anonymer Geräte-Fingerprint + Lizenzschlüssel alle 24 h an `api.annmax1983.com` gesendet. Es werden keine Browserdaten übertragen.

**[📄 Datenschutzerklärung](../privacy-policy.html)**

---

## Lizenz

Copyright © 2026 RefreshMate. Alle Rechte vorbehalten.

---

> **Hinweis:** Dieses Repository dient **nur der Projekt-Präsentation**.
