# RefreshMate

[English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | Deutsch | [Español](README_es.md) | [Français](README_fr.md)

Eine schlanke Browser-Erweiterung für anpassbares automatisches Seiten-Neuladen mit zufälligen Intervallen und Keyword-Änderungsalarmen.

> Chromium-basiert · Manifest V3 · Minimale Berechtigungen · Nur lokal

---

## Warum RefreshMate?

Du möchtest eine Seite auf Änderungen überwachen? RefreshMate lädt Seiten nach deinem Zeitplan neu und alarmiert dich, wenn Keywords erscheinen oder verschwinden — ideal für Aktienüberwachung, Ticketverkauf oder jede zeitkritische Seite.

| Vorteil | Details |
|---------|---------|
| ⏱️ **Eigene Intervalle** | Schnelle Voreinstellungen (5s/30s/1min/5min) + benutzerdefinierte Eingabe |
| 🎲 **Zufälliges Intervall** | Anti-Erkennung durch Zufallsbereich, um Seitenblockaden zu vermeiden |
| 🔔 **Keyword-Alarme** | Browser-Benachrichtigungen bei Erscheinen/Verschwinden von Keywords |
| 🔒 **CAPTCHA-Erkennung** | Stoppt das Neuladen automatisch bei erkanntem CAPTCHA |
| 💾 **Einstellungen pro Seite** | Jede Domain speichert ihre eigene Konfiguration unabhängig |

---

## Funktionen

| Funktion | Beschreibung |
|----------|--------------|
| ⏱️ **Auto-Neuladen** | Intervalle von 5 Sekunden bis Stunden einstellen |
| 🎲 **Zufallsbereich** | Min/Max-Bereich setzen, Intervall wird jeden Zyklus randomisiert |
| 🧹 **Hard Refresh** | Cache umgehen mit Strg+Umschalt+R-artigem Reload |
| 🔔 **Keyword-Überwachung** | Alarm bei Text auf der Seite, der erscheint oder verschwindet |
| ⚠️ **CAPTCHA-Stopp** | Erkennt gängige CAPTCHA-Muster, stoppt automatisch |
| 🖼️ **Schwebendes Overlay** | Mini-Countdown-Timer auf der Seite |
| ⌨️ **Auto-Pause** | Pausiert bei Eingabe in Eingabefeldern |
| 💾 **Domain-Speicher** | Einstellungen pro Seite werden automatisch gespeichert |

---

## Kostenlos vs. Pro

| Funktion | Kostenlos | Pro (Lizenz) |
|----------|-----------|---------------|
| 🗂️ **Gleichzeitige Tabs** | **1 Tab** gleichzeitig | ✅ Unbegrenzt |
| 🎲 **Zufälliger Intervallbereich** | — | ✅ |
| 🔔 **Keyword / Regex Alarme** | — | ✅ |
| 🔄 **Erkennung jeder Seitenänderung** | — | ✅ |
| 🆘 **Priority Support** | — | ✅ |

Die kostenlose Version aktualisiert **nur einen Tab gleichzeitig** im gesamten Browser. Upgrade auf Pro, um mehrere Tabs gleichzeitig zu aktualisieren.

---

## Unterstützte Browser

| Browser | Status |
|---------|--------|
| Google Chrome | ✅ Vollständig unterstützt |
| Microsoft Edge | ✅ Vollständig unterstützt |
| Andere Chromium-basierte | ✅ Sollte funktionieren |

---

## Installation

1. Repository klonen oder herunterladen
2. Öffne `chrome://extensions/` (oder `edge://extensions/`)
3. Aktiviere den **Entwicklermodus**
4. Klicke auf **Entpackte Erweiterung laden** → wähle den Ordner `RefreshMate`
5. Klicke auf das 🔄 RefreshMate-Symbol zum Starten

### Build

```bash
npm install
npm run build
```

---

## Datenschutz

- **activeTab** — Zugriff auf den aktuellen Tab bei Interaktion mit der Erweiterung
- **tabs** — Findet Tabs zum Neuladen nach Domain
- **storage** — Einstellungen lokal speichern
- **alarms** — Refresh-Timer planen
- **notifications** — Browser-Benachrichtigungen für Keyword-Alarme
- **Lizenzvalidierung** — Anonymer Geräte-Fingerprint + Lizenzschlüssel wird einmal alle 24h an `api.annmax1983.com` gesendet. Keine Browserdaten übertragen.

**[📄 Datenschutzerklärung](privacy-policy.html)**

---

## Lizenz

Copyright © 2026 RefreshMate. Alle Rechte vorbehalten.

---

> **Hinweis:** Dieses Repository dient ausschließlich der **Projektpräsentation**.
