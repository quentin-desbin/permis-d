# 🚌 Objectif Permis D — Révision des Fiches Écrites (2026)

Application web interactive et autonome permettant de réviser l'intégralité des **20 fiches écrites officielles (200 questions)** de l'épreuve hors circulation du **Permis D** (transport en commun de personnes).

Conçue pour reproduire les conditions réelles de l'examen, elle permet de s'entraîner « du tac au tac » sans indice sur le numéro de la fiche tirée, avec validation groupée après chaque série de 10 questions.

---

## ✨ Fonctionnalités principales

- **🎲 Tirage au sort intelligent** : Sélectionne une fiche complète parmi les 20 fiches officielles en priorisant celles qui n'ont pas encore été révisées (progression sauvegardée localement dans le navigateur).
- **🙈 Conditions réelles d'examen** : Le numéro de la fiche reste masqué tout au long de l'épreuve et n'est révélé qu'au moment du bilan final.
- **⚡ Mode Examen « Tac au tac » (par défaut)** :
  - Entraînement sans QCM pour répondre spontanément à l'oral ou via une saisie rapide au clavier (`Entrée` pour enchaîner).
  - Correction automatique tolérante (accents, casse, formulations équivalentes) complétée par un bouton d'**auto-évaluation** sur l'écran de bilan pour valider vos réponses orales.
- **🎯 Mode Entraînement (QCM)** : 4 propositions par question pour mémoriser les notions réglementaires et techniques.
- **🛑 Panneaux routiers illustrés** : Représentations vectorielles (SVG) haute netteté intégrées directement aux questions de signalisation.
- **🌓 Thème Clair / Sombre (Dark Mode)** : Bascule instantanée avec détection automatique des préférences système.
- **📦 100 % autonome (Zero-Backend)** : Un unique fichier `index.html` sans dépendance serveur ni base de données.

---

## 🚀 Déploiement et utilisation

### Utilisation en ligne (GitHub Pages)
Accéder à https://quentin-desbin.github.io/permis-d/ pour pouvoir utiliser l'application

### Utilisation locale (hors ligne)
Clonez le dépôt ou téléchargez simplement le fichier `index.html`, puis ouvrez-le dans n'importe quel navigateur web moderne (Chrome, Firefox, Safari, Edge) — aucune installation requise.

```bash
git clone https://github.com/<votre-utilisateur>/<votre-depot>.git
cd <votre-depot>
```

---

## 🛠️ Stack technique

- **HTML5 / JavaScript Vanilla (ES6+)** : Logique de tirage, chronomètre, normalisation et évaluation des réponses, sauvegarde dans `localStorage`.
- **Tailwind CSS (via CDN)** : Interface responsive inspirée des plateformes modernes d'apprentissage de la conduite.
- **SVG natif** : Favicon personnalisé et panneaux de signalisation routière intégrés.

---

## ⚠️ Avertissement

Ce projet est un outil personnel d'aide à la révision basé sur le référentiel des interrogations écrites de la catégorie D (édition 2026). Il n'est affilié à aucun organisme officiel ni éditeur pédagogique.