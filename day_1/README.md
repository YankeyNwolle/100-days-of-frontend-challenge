# 100 Days Frontend — Challenge Day 1

## Description
Projet personnel dans le cadre d'un challenge "100 jours de code" : recréer une interface mobile de profil / menu en HTML, CSS et JavaScript. L'objectif est d'appliquer les bonnes pratiques, d'explorer l'interactivité et d'améliorer progressivement la solution.

## User Story
En tant qu'utilisateur, je veux une interface mobile intuitive qui me permette de naviguer facilement dans les réglages et options de mon profil pour améliorer mon expérience d'application.

## Critères d'acceptation
- Le nom de l'utilisateur et sa profession s'affichent en haut du menu.
- Les éléments de menu suivants sont présents et accessibles : Personal Data, Messages, Notifications, Location, Community, FAQs, Settings.
- Chaque élément a une icône représentative.
- Les zones cliquables sont assez grandes pour un usage mobile.
- Le design est responsive et lisible sur différents appareils/ orientations.

## Démarrage rapide
1. Ouvrir le fichier `day_1/index.html`.
2. Éditer `day_1/style.css` pour le style.
3. Ajouter des interactions dans `day_1/script.js` (créer le fichier si nécessaire).
4. Ouvrir dans le navigateur ou utiliser Live Server (VS Code).

## Structure recommandée
- day_1/
  - index.html
  - style.css
  - script.js
  - assets/ (images, icônes)

## Bonnes pratiques & conseils
- Respecter le design (marges, typographie, alignements).
- Utiliser Flexbox / Grid pour les mises en page responsives.
- Optimiser les images (webp / compression).
- Tester sur mobile (outil de développement du navigateur).
- Commenter et structurer le code pour maintenir la lisibilité.

## Fonctionnalités recommandées pour travailler ta créativité
Ajoute une ou plusieurs de ces fonctionnalités pour progresser :
- Mode sombre / clair (bouton qui bascule les variables CSS).
  - Implémentation : variables CSS + JS pour ajouter/enlever une classe sur <body>.
- Animation d'ouverture/fermeture du menu (transition slide ou scale).
  - Implémentation : CSS transitions + classes toggled via JS.
- Indicateurs de badge (nouveaux messages / notifications).
  - Implémentation : petit badge en CSS et mise à jour via JS.
- Édition du profil inline (clic sur le nom ouvre un champ éditable).
  - Implémentation : contenteditable ou formulaire modal.
- LocalStorage pour sauvegarder les préférences (mode sombre, état du menu).
- Accessibilité : focus visible, aria-labels, tailles de cible minimum (44–48px).
- Micro-interactions : hover, active, ripple effect mobile simulé.



## Tests & QA
- Vérifier sur différents viewport (iPhone/Android).
- Tester la taille des zones cliquables et la lisibilité.
- Valider l'absence d'erreurs JS dans la console.

## Déploiement rapide
- Héberger sur GitHub Pages : pousser le repo et activer Pages sur la branche principale.
- Ou utiliser Netlify / Vercel pour déploiement instantané.

