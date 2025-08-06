# DeepSite-to-N8n

Ce dépôt regroupe les **résultats HTML/CSS/JS générés par DeepSite**, à partir des prompts issus du dépôt `GPT-to-DeepSite`.  
Il contient les composants, templates et scripts prêts à être injectés dans des workflows N8n pour automatiser le déploiement de sites.

---

## 🎯 Objectif

Créer une **bibliothèque modulaire et interopérable** :

- Blocs HTML/CSS prêts à l’emploi
- Templates dynamiques pour Kajabi, WordPress ou SaaS custom
- Scripts d’intégration (DeepSite → N8n → Hostinger/Vercel)
- Préparation RGPD, SEO et accessibilité
- Base de données pour automatiser le déploiement depuis Olympus

---

## 📁 Structure recommandée

- `/sites/` → Un dossier par site ou domaine final
- `/templates/` → Templates modulaires HTML, WordPress, Kajabi…
- `/scripts/` → Scripts d’export, intégration N8n, injection balises
- `/deploy/` → Préparations spécifiques à Hostinger, Vercel, S3
- `/meta/` → README, changelogs, glossaire, versions

---

## 🔄 Connexions

- Prompt source : `GPT-to-DeepSite`
- Génération : via DeepSite V2
- Automatisation : via modules N8n et Olympus
- Dépôt parent : `SPUP-hub`

Mainteneur : Stéphane Pariente  
Organisation : SPUP-hub
