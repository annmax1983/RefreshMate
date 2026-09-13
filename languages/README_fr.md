# RefreshMate

[English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | [Español](README_es.md) | Français

Une extension légère pour rafraîchir automatiquement les pages avec des intervalles personnalisables et des alertes par mot-clé.

> Chromium · Manifest V3 · Permissions minimales · 100 % local

---

## Pourquoi RefreshMate ?

Vous devez surveiller une page pour détecter des changements ? RefreshMate rafraîchit automatiquement les pages selon votre planning et vous alerte quand des mots-clés apparaissent ou disparaissent — idéal pour surveiller des stocks, des billets ou toute page sensible au temps.

| Avantage | Détail |
|-----------|--------|
| ⏱️ **Intervalles personnalisables** | Préréglages rapides (5s/30s/1min/5min) + saisie personnalisée |
| 🎲 **Intervalle aléatoire** | Plage aléatoire anti-détection pour éviter les blocages de sites |
| 🔔 **Alertes par mot-clé** | Notifications du navigateur quand des mots-clés apparaissent/disparaissent |
| 🔒 **Détection de CAPTCHA** | Arrêt automatique du rafraîchissement en cas de CAPTCHA détecté |
| 💾 **Paramètres par site** | Chaque domaine sauvegarde sa propre configuration indépendamment |

---

## Fonctionnalités

| Fonctionnalité | Description |
|---------|-------------|
| ⏱️ **Rafraîchissement automatique** | Réglez des intervalles de 5 secondes à plusieurs heures |
| 🎲 **Plage aléatoire** | Définissez une plage min/max, l'intervalle est randomisé à chaque cycle |
| 🧹 **Rafraîchissement forcé** | Contournement du cache avec un rechargement de type Ctrl+Shift+R |
| 🔔 **Surveillance par mot-clé** | Alerte quand un texte apparaît ou disparaît sur la page |
| ⚠️ **Arrêt sur CAPTCHA** | Détecte les motifs de CAPTCHA courants, arrêt automatique |
| 🖼️ **Overlay flottant** | Mini compte à rebours sur la page |
| ⫶️ **Pause automatique** | Met en pause quand vous saisissez du texte dans un champ |
| 💾 **Mémoire par domaine** | Paramètres par site sauvegardés automatiquement |

---

## Gratuit vs Pro

| Capacité | Gratuit | Pro (Licence) |
|------------|------|----------------|
| 🗂️ **Onglets simultanés** | **1 onglet** à la fois | ✅ Illimité |
| 🎲 **Plage d'intervalle aléatoire** | — | ✅ |
| 🔔 **Alertes par mot-clé / regex** | — | ✅ |
| 🔄 **Détection de tout changement de page** | — | ✅ |
| 🆘 **Support prioritaire** | — | ✅ |

La version gratuite ne rafraîchit qu'**un seul onglet à la fois** dans l'ensemble du navigateur. Passez à Pro pour rafraîchir plusieurs onglets simultanément.

---

## Navigateurs compatibles

| Navigateur | Statut |
|---------|--------|
| Google Chrome | ✅ Entièrement pris en charge |
| Microsoft Edge | ✅ Entièrement pris en charge |
| Autres navigateurs basés sur Chromium | ✅ Devrait fonctionner |

---

## Installation

1. Clonez ou téléchargez ce dépôt
2. Ouvrez `chrome://extensions/` (ou `edge://extensions/`)
3. Activez le **mode Développeur**
4. Cliquez sur **Charger le package décompressé** → sélectionnez le dossier `RefreshMate`
5. Cliquez sur l'icône 🔄 RefreshMate pour commencer

### Build

```bash
npm install
npm run build
```

---

## Confidentialité

- **activeTab** — Accède à l'onglet actif quand vous interagissez avec l'extension
- **tabs** — Recherche les onglets à rafraîchir par domaine
- **storage** — Sauvegarde les paramètres en local
- **alarms** — Planifie les minuteurs de rafraîchissement
- **notifications** — Notifications du navigateur pour les alertes par mot-clé
- **Validation de licence** — empreinte anonyme de l'appareil + clé de licence envoyées à `api.annmax1983.com` une fois toutes les 24h. Aucune donnée de navigation transmise.

**[📄 Politique de confidentialité](privacy-policy.html)**

---

## Licence

Copyright © 2026 RefreshMate. Tous droits réservés.

---

> **Note :** Ce dépôt est destiné à la **présentation du projet uniquement**.
