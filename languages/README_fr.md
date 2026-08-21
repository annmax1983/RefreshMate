# RefreshMate
[English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | [Español](README_es.md) | Français

Une extension de navigateur légère pour actualiser automatiquement les pages à intervalles configurables avec alertes sur les changements de mots-clés.

> Basé sur Chromium · Manifest V3 · Permissions minimales · Uniquement local

---

## Pourquoi RefreshMate ?

Besoin de surveiller une page ? RefreshMate actualise automatiquement les pages selon votre planning et vous alerte lorsqu'un mot-clé apparaît ou disparaît — idéal pour le suivi d'actions, la vente de billets ou toute page sensible au facteur temps.

| Avantage | Détail |
|----------|--------|
| ⏱️ **Intervalles personnalisés** | Préréglages rapides (5s/30s/1min/5min) + saisie personnalisée |
| 🎲 **Intervalle aléatoire** | Plage aléatoire anti-détection pour éviter les blocages |
| 🔔 **Alertes de mots-clés** | Notifications du navigateur à l'apparition/disparition |
| 🔒 **Détection CAPTCHA** | Arrête l'actualisation automatiquement si CAPTCHA détecté |
| 💾 **Réglages par site** | Chaque domaine enregistre sa configuration indépendamment |

---

## Fonctionnalités

| Fonction | Description |
|----------|-------------|
| ⏱️ **Actualisation automatique** | Intervalles de 5 secondes à plusieurs heures |
| 🎲 **Plage aléatoire** | Intervalle min/max, randomisé à chaque cycle |
| 🧹 **Actualisation forcée** | Contourne le cache (style Ctrl+Shift+R) |
| 🔔 **Surveillance des mots-clés** | Alerte à l'apparition ou la disparition de texte |
| ⚠️ **Arrêt CAPTCHA** | Détecte les motifs CAPTCHA courants, arrêt automatique |
| 🖼️ **Superposition flottante** | Mini compte à rebours sur la page |
| ⌨️ **Pause automatique** | Pause lors de la saisie dans un champ |
| 💾 **Mémoire de domaine** | Réglages par site enregistrés automatiquement |

---

## Gratuit vs. Pro

| Fonction | Gratuit | Pro (Licence) |
|----------|---------|---------------|
| 🗂️ **Onglets simultanés** | **1 seul onglet** à la fois | ✅ Illimité |
| 🎲 **Plage d'intervalle aléatoire** | — | ✅ |
| 🔔 **Alertes mots-clés / regex** | — | ✅ |
| 🔄 **Détection de tout changement** | — | ✅ |
| 🆘 **Support prioritaire** | — | ✅ |

La version gratuite actualise **un seul onglet à la fois** dans tout le navigateur. Passez à Pro pour actualiser plusieurs onglets simultanément.

---

## Navigateurs pris en charge

| Navigateur | Statut |
|------------|--------|
| Google Chrome | ✅ Entièrement pris en charge |
| Microsoft Edge | ✅ Entièrement pris en charge |
| Autres basés sur Chromium | ✅ Devrait fonctionner |

---

## Installation

1. Clonez ou téléchargez ce dépôt
2. Ouvrez `chrome://extensions/` (ou `edge://extensions/`)
3. Activez le **mode développeur**
4. Cliquez sur **Charger l'extension non empaquetée** → sélectionnez le dossier `RefreshMate`
5. Cliquez sur l'icône 🔄 RefreshMate pour commencer

### Compilation

```bash
npm install
npm run build
```

---

## Confidentialité

- **activeTab** — Accède à l'onglet actuel lors de l'interaction
- **tabs** — Trouve les onglets à actualiser par domaine
- **storage** — Enregistre les réglages localement
- **alarms** — Planifie les minuteries d'actualisation
- **notifications** — Notifications du navigateur pour les alertes de mots-clés
- **Validation de licence** — empreinte d'appareil anonyme + clé de licence envoyées à `api.annmax1983.com` toutes les 24 h. Aucune donnée de navigation transmise.

**[📄 Politique de confidentialité](../privacy-policy.html)**

---

---

## Avis sur le code source

> ⚠️ **Ce dépôt ne publie pas le code source.** Il contient uniquement la documentation d'utilisation, les notes de mise à jour et les ressources d'assistance. L'extension est distribuée exclusivement via le Chrome Web Store. Aucun package d'installation hors ligne ni code source pour les utilisateurs finaux n'est fourni.


## Licence

Copyright © 2026 RefreshMate. Tous droits réservés.

---

> **Note :** Ce dépôt est **uniquement destiné à la présentation du projet**.
