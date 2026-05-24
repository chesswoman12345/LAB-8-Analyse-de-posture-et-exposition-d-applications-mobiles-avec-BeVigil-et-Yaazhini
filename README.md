# 🔐 LAB 8 — Analyse de posture et exposition d’applications mobiles avec BeVigil et Yaazhini

> Analyse défensive mobile — Audit de posture de sécurité Android  
> Outils utilisés : BeVigil & Yaazhini  
> Niveau : Débutant / Intermédiaire

---

# 📌 Présentation du Lab

Ce laboratoire pédagogique introduit l’analyse défensive de la posture de sécurité d’applications mobiles Android à l’aide de deux outils :

- **BeVigil** → collecte d’informations exposées publiquement
- **Yaazhini** → analyse interne approfondie d’un APK

L’objectif est de :

- cartographier la surface d’exposition d’une application mobile ;
- identifier des signaux de sécurité potentiellement risqués ;
- distinguer les vrais constats des faux positifs ;
- corréler les résultats avec les standards OWASP MASVS ;
- produire un rapport professionnel exploitable.

---

# ⚠️ Règles & Éthique

## ✅ Autorisé

Travailler UNIQUEMENT sur :

- un APK pédagogique fourni par l’enseignant ;
- une application interne autorisée ;
- un domaine explicitement autorisé.

## ❌ Interdit

- Exploiter les vulnérabilités découvertes
- Effectuer des tests intrusifs
- Contourner des protections
- Scanner des cibles non autorisées
- Exposer des secrets ou données sensibles

---

# 🎯 Objectifs pédagogiques

À la fin de ce lab, l’apprenant sera capable de :

- Organiser un audit défensif d’application mobile
- Collecter des signaux d’exposition avec BeVigil et Yaazhini
- Trier les résultats et identifier les faux positifs
- Corréler les constats avec les standards OWASP
- Produire un rapport d’analyse exploitable

---

# 🧰 Outils Utilisés

| Outil | Rôle |
|---|---|
| BeVigil | Collecte d’exposition externe |
| Yaazhini | Analyse interne APK |
| PowerShell | Automatisation |
| OWASP MASVS | Référentiel sécurité |
| Windows | Environnement du lab |

---

# 📂 Structure du Projet

```bash
lab-mobile-security/
│
├── 00-scope/
├── 01-bevigil/
├── 02-yaazhini/
├── 03-triage/
├── 04-report/
│
├── analyse_info.txt
├── commands.log
└── checklist_fin.md
