# STAMM — Serveur Terminal Autonome Messagerie Mobile

![STAMM](https://www.pierre-lannes.fr/wp-content/uploads/2025/08/paysage-stamm.jpg)

![License: OHL-S](https://img.shields.io/badge/Hardware-CERN_OHL--S_v2-blue.svg)
![License: AGPL](https://img.shields.io/badge/Software-AGPL--3.0-orange.svg)
![License: CC BY](https://img.shields.io/badge/Docs-CC_BY_4.0-lightgrey.svg)
![GitHub Pages](https://img.shields.io/badge/Docs-online-brightgreen.svg)

---

## 🚨 Contexte
**STAMM** est un prototype de kit de communication et de services mobiles **décentralisés** utilisable :  
- en **zone blanche** (sans réseau),  
- en situation **dégradée** (panne électricité, réseau, internet),  
- pour des missions de **gestion de crise, secours et intervention**.

Le système est pensé comme **autonome**, compact (valise étanche) et modulaire.

👉 Présentation complète du projet :  
[Article sur pierre-lannes.fr](https://www.pierre-lannes.fr/cyberdeck-stamm-resilience-numerique/)

---

## ⚙️ Fonctionnalités ouvertes
- Serveur SIG (cartographies locales, QGIS Server ou équivalent)  
- Wiki collaboratif local (MediaWiki)  
- Médiathèque locale (DLNA)  
- Relais radio (HF/VHF/UHF, LoRa/Meshtastic)  
- Point d’accès Wi-Fi et connexion Ethernet

---

## 📂 Structure du dépôt
- `docs/` → Documentation utilisateur (publiée via GitHub Pages)  
- `software/` → Configurations logicielles de base (Docker Compose minimal)  
- `hardware/` → Descriptions matérielles principales (liste et infos publiques)  
- `LICENSE.HARDWARE`, `LICENSE.SOFTWARE`, `LICENSE.DOCS` → Textes de licences distincts  
- `NOTICE` → Récapitulatif de la portée des licences  

---

## 📜 Licences
- **Hardware** (`hardware/`) : [CERN OHL-S v2](https://ohwr.org/cern_ohl_s_v2.txt)  
  *(plans et schémas techniques seulement)*  
- **Software** (`software/`) : [AGPL-3.0-or-later](https://www.gnu.org/licenses/agpl-3.0.txt)  
- **Documentation** (`docs/`) : [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode)  

---

## 🌐 Documentation en ligne
👉 La documentation est publiée automatiquement sur **GitHub Pages** :  
[https://pierrelga456.github.io/stamm/](https://pierrelga456.github.io/stamm/)

---

## ⚠️ Limites de la version publique
- Les **détails mécaniques**, les **gabarits internes** et certaines optimisations ne sont **pas publiés**.  
- Ils sont conservés dans un dépôt **privé** (notes internes et variantes).  

---
