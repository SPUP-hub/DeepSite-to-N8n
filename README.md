# DeepSite-to-N8n

Ce dépôt regroupe les **résultats générés par DeepSite**, à partir des prompts du dépôt `GPT-to-DeepSite`.  
Il contient les **pages HTML, blocs réutilisables, composants CSS et JS**, prêts à être injectés dans des workflows N8n pour un déploiement automatisé.

---

## 🎯 Objectif

Structurer une bibliothèque réutilisable, modulable et connectable dans N8n :

- Blocs HTML prêts à l’emploi (carousel, header, testimonials, CTA…)
- Pages complètes générées via DeepSite
- Scripts dynamiques et snippets JS utiles pour enrichir les templates

---

## 📁 Arborescence

- `/components/` : tous les blocs HTML/CSS générés
- `/outputs/` : pages complètes (index.html, landing.html…)
- `/meta/` : fichiers annexes (README, journal de génération, logs…)

---

## 🔄 Connexions

- Dépôt source : `GPT-to-DeepSite`
- Dépôt parent : `SPUP-hub`
- Déploiement : destiné à être utilisé dans les workflows N8n via automatisation Olympus

Mainteneur : Stéphane Pariente  
Organisation : SPUP-hub
