---
title: "Design system : de quoi c’est fait et comment ça marche"
date: 2026-01-23
tags: ["design systems", "UX UI"]
categories: ["Design"]
draft: false
---

## De quoi parle ces articles ?

Un design system est un ensemble de standards destiné à gérer le design à grande échelle en réduisant la redondance, tout en créant un langage partagé et une cohérence visuelle entre produits.  
Il sert de référentiel commun pour les équipes design et développement, avec des composants, patterns, styles et guidelines.  

## Ce que j’en retiens en détail

Un design system ne se limite pas à “une librairie de composants” : il contient généralement un repository (styles, composants, patterns, documentation) mais il dépend aussi d’une équipe qui le maintient et le fait évoluer, sinon il devient vite incohérent ou obsolète.  

Le contenu concret d’un design system ressemble à un kit complet : typographie, palettes de couleurs, grilles, iconographie, règles de communication (ton), composants UI et patterns réutilisables. L’intérêt est de gagner en cohérence et en efficacité, et de réduire la “dette design” et la “dette technique”.  

Pour comprendre comment “ça marche” dans la pratique, les design tokens sont une pièce importante : ce sont des décisions de design représentées sous forme de données (couleurs, tailles de texte, espacements, etc.) afin d’éviter des valeurs écrites en dur et faciliter la cohérence entre design et code.  

Une façon simple d’expliquer leur structure est la hiérarchie suivante : token global (valeur primitive), token alias (usage sémantique), token relatif (variante selon le contexte). Cette organisation aide à garder la cohérence tout en gérant des cas d’usage réels (CTA, cartes, thèmes).  

## Pourquoi ça m’intéresse et pourquoi c’est utile pour moi

Ce sujet m’aide à clarifier la différence entre “faire des composants” et construire un système complet : il faut aussi des règles, une documentation et une maintenance dans le temps.  
Comprendre les tokens me permet aussi de voir comment transformer des choix visuels (couleurs, typo, spacing) en décisions réutilisables et évolutives.  

## À quel moment ce sera utile pour moi

Ce sera utile au moment de structurer des foundations (couleurs, typo, spacing) et de garantir leur cohérence dans tous les composants.  
Ce sera aussi utile quand il faudra faire évoluer un produit (ajouts, refonte, variantes, theming), car un design system bien organisé permet de changer plus vite et avec moins de risques.  

## Comment je les ai trouvés

Après mes premiers articles (pixel perfect et skeleton screens), je me suis rendu compte que je comprenais bien certains principes et patterns, mais que je voulais mieux saisir “comment fonctionne” un design system dans son ensemble. J’ai donc fait des recherches complémentaires et j’ai recoupé plusieurs ressources plus générales (NN/g et Usabilis) ainsi que des articles plus ciblés sur les design tokens (Usabilis et Bewizyu), pour clarifier ce qu’on retrouve concrètement dans un design system et comment les décisions UI peuvent être structurées et réutilisées.

## Source

- https://www.nngroup.com/articles/design-systems-101/
- https://usabilis.com/design-system/#lire
- https://usabilis.com/design-tokens-comprendre-utiliser/
- https://www.bewizyu.com/blog/les-design-tokens-pour-les-nuls
