# CLAUDE.md — Répertoire de Recettes

## Vue d'ensemble

Ce répertoire contient une collection de recettes organisées par catégorie. Ce fichier guide Claude pour naviguer, créer et modifier des recettes de manière cohérente.

---

## Structure du répertoire

```
recettes/
├── entrees/          # Entrées et amuse-bouches
├── plats/            # Plats principaux
│   ├── viandes/
│   ├── poissons/
│   └── vegetarien/
├── desserts/         # Desserts et pâtisseries
├── boissons/         # Boissons, cocktails, smoothies
├── bases/            # Sauces, bouillons, pâtes de base
└── INDEX.md          # Index global des recettes
```

---

## Format standard d'une recette

Chaque recette est un fichier `.md` nommé en `kebab-case` (ex. `tarte-tatin.md`).

```markdown
# Nom de la recette

**Catégorie** : plat principal / dessert / entrée / ...  
**Cuisine** : française / italienne / asiatique / ...  
**Difficulté** : facile / moyen / difficile  
**Temps de préparation** : X min  
**Temps de cuisson** : X min  
**Portions** : X personnes  

## Description

Courte description appétissante de la recette (2-3 phrases).

## Ingrédients

- X tasse / c. à soupe / c. à thé / lb / oz d'ingrédient
- ...

## Instructions

1. Étape claire et concise.
2. ...

## Notes & variantes

Conseils, substitutions possibles, suggestions d'accompagnement.

## Tags

`#tag1` `#tag2` `#tag3`
```

---

## Conventions

- **Unités** : utiliser les mesures courantes en cuisine québécoise —
  - Volumes : tasse (250 ml), c. à soupe (15 ml), c. à thé (5 ml), pinte, chopine
  - Poids : lb (livre), oz — grammes acceptés pour la boulangerie/pâtisserie
  - Températures : °F pour les fours (°C entre parenthèses en option), ex. `350 °F (175 °C)`
  - Dimensions : pouces (po) pour les moules et plats de cuisson
- **Langue** : toutes les recettes sont rédigées en français.
- **Noms de fichiers** : `kebab-case`, sans accents (ex. `boeuf-bourguignon.md`).
- **Tags communs** : `#végétarien`, `#vegan`, `#sans-gluten`, `#rapide`, `#fait-maison`, `#économique`.
- **Températures de cuisson** : toujours en Fahrenheit (°F), avec °C entre parenthèses si souhaité.
- **Portions par défaut** : 4 personnes, sauf indication contraire.

---

## Tâches fréquentes

### Ajouter une recette
Créer un nouveau fichier `.md` dans le bon sous-dossier en respectant le format standard ci-dessus, puis mettre à jour `INDEX.md`.

### Modifier une recette
Conserver la structure existante ; noter les modifications importantes dans la section **Notes & variantes**.

### Rechercher une recette
Consulter `INDEX.md` ou parcourir les sous-dossiers par catégorie. Les tags permettent également une recherche transversale.

### Convertir les portions
Adapter les quantités proportionnellement. Signaler si certains ingrédients (levure, gélatine, épices) ne se scalent pas linéairement.

---

## Bonnes pratiques pour Claude

- Toujours vérifier qu'une recette similaire n'existe pas déjà avant d'en créer une nouvelle.
- Privilegier des instructions précises et actionnables (températures exactes, textures à obtenir, durées).
- Proposer des substitutions pour les ingrédients difficiles à trouver.
- Mentionner les allergènes courants (gluten, lactose, fruits à coque, œufs) dans les notes si pertinent.
- Ne pas inventer des recettes sans base culinaire réelle ; s'appuyer sur des techniques éprouvées.