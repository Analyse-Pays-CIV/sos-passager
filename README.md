# ✈️ SOS PASSAGER — Plateforme d'indemnisation vol

> **Vos droits. Notre combat. Jusqu'à 600€ d'indemnisation.**

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-1B7A3E?style=for-the-badge&logo=github)](https://Analyse-Pays-CIV.github.io/sos-passager)
[![Licence](https://img.shields.io/badge/Licence-Open%20Source-F5A623?style=for-the-badge)](LICENSE)
[![CE 261/2004](https://img.shields.io/badge/R%C3%A8glement-CE%20261%2F2004-1B7A3E?style=for-the-badge)](https://eur-lex.europa.eu/legal-content/FR/TXT/?uri=CELEX:32004R0261)
[![UEMOA](https://img.shields.io/badge/R%C3%A8glement-UEMOA%20N%C2%B003%2F2003-F5A623?style=for-the-badge)](https://sos-passager.site123.me)

---

## 🌍 À propos

**SOS PASSAGER** est une plateforme web complète de défense des droits des passagers aériens, opérant en **Europe** et en **Afrique de l'Ouest (UEMOA)**.

Développée par **Ivoire Consulting / AICDI** (Freiburg im Breisgau 🇩🇪 · Abidjan 🇨🇮), cette plateforme permet aux passagers victimes de retards, annulations ou surbookings de :

- Vérifier leur éligibilité à une indemnisation
- Calculer le montant auquel ils ont droit
- Déposer leur réclamation en ligne
- Signer électroniquement le mandat de représentation
- Suivre leur dossier en temps réel

---

## ⚡ Fonctionnalités

| Fonctionnalité | Description |
|---|---|
| 🔍 **Calculateur CE 261/2004** | Calcul en 5 étapes — retard, annulation, surbooking, correspondance |
| 🌍 **Calculateur UEMOA** | Couverture Afrique de l'Ouest — jusqu'à 1 219 € |
| ✈️ **Vérification vol temps réel** | API AviationStack — statut du vol en direct |
| 📝 **Formulaire de réclamation** | Dépôt complet avec pièces justificatives |
| ✍️ **Signature électronique** | Mandat signé directement dans le navigateur (canvas) |
| 👤 **Espace client** | Suivi de dossier, timeline, statut en temps réel |
| 🔔 **Notifications email** | Alertes à chaque étape (EmailJS / SMTP) |
| 📰 **Blog juridique** | Actualités CE 261, UEMOA, jurisprudence |
| 📱 **100% responsive** | Mobile, tablette, desktop |

---

## 🗺️ Couverture géographique

### 🇪🇺 Europe — Règlement CE 261/2004
| Distance | Indemnisation |
|---|---|
| < 1 500 km | **250 €** |
| 1 500 – 3 500 km | **400 €** |
| > 3 500 km | **600 €** |

### 🌍 Afrique de l'Ouest — Règlement UEMOA N°03/2003
Pays couverts : Côte d'Ivoire · Sénégal · Mali · Burkina Faso · Togo · Bénin · Niger · Guinée-Bissau

| Distance | Indemnisation |
|---|---|
| Courts courriers | **200 €** |
| Moyens courriers | **400 €** |
| Maximum | **1 219 €** |

---

## 🚀 Installation & Déploiement

### Option 1 — GitHub Pages (recommandé, gratuit)
```bash
# 1. Forker ce dépôt
# 2. Aller dans Settings → Pages
# 3. Source : Deploy from branch → main → / (root)
# 4. Site disponible sur : https://VOTRE-USERNAME.github.io/sos-passager
```

### Option 2 — Hébergement local
```bash
git clone https://github.com/Analyse-Pays-CIV/sos-passager.git
cd sos-passager
# Ouvrir index.html dans votre navigateur
open index.html
```

---

## 🔑 Configuration API

### AviationStack (vérification vol temps réel)
1. Créer un compte gratuit sur [aviationstack.com](https://aviationstack.com)
2. Copier votre clé API gratuite
3. Dans `index.html`, remplacer :
```javascript
const API_KEY = 'YOUR_AVIATIONSTACK_KEY';
```
par votre vraie clé.

### EmailJS (notifications email, gratuit)
1. Créer un compte sur [emailjs.com](https://emailjs.com)
2. Configurer votre template d'email
3. Intégrer le SDK EmailJS dans le fichier

---

## 📁 Structure du projet

```
sos-passager/
│
├── index.html          # Application complète (single-page)
└── README.md           # Ce fichier
```

---

## 📞 Contact

| Bureau | Coordonnées |
|---|---|
| 🇩🇪 **Europe — Freiburg** | Burgackerweg 4, 79104 Freiburg im Breisgau |
| | 📞 +49 (0)761 55 44 82 |
| | 💬 WhatsApp : +49 177 343 14 60 |
| 🇨🇮 **Afrique — Abidjan** | Bd Cité du Port, Villa 46, ABATTA Cocody |
| | 💬 WhatsApp : +225 05 03 60 57 25 |
| 📧 **Email** | info@sos-passager.com |
| 🌐 **Site** | [sos-passager.site123.me](https://sos-passager.site123.me) |

---

## ⚖️ Cadre juridique

- **Règlement CE 261/2004** du Parlement européen et du Conseil
- **Règlement N°03/2003/CM/UEMOA** relatif aux droits des passagers aériens
- Commission de succès : 20–30% + TVA (éventuellement + 14% frais d'avocat)
- **Sans succès = sans frais**

---

## 🛠️ Technologies utilisées

- HTML5 / CSS3 / JavaScript vanilla
- Font Awesome 6.5 (icônes)
- Unsplash API (images libres de droits)
- AviationStack API (données vols temps réel)
- GitHub Pages (hébergement)

---

*© 2025 SOS PASSAGER — Ivoire Consulting / AICDI · Freiburg im Breisgau 🇩🇪 · Abidjan 🇨🇮*
