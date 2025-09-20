---
tags: [MPSI, Algèbre, Espaces vectoriels]
---

# Algèbre – Espaces vectoriels

## Définitions essentielles
- **Espace vectoriel (EV)** : ensemble \(E\) muni d'une addition et d'une multiplication par un scalaire satisfaisant les axiomes.
- **Sous-espace vectoriel (SEV)** : sous-ensemble non vide stable par addition et multiplication par un scalaire.
- **Famille génératrice** : \(\{v_1,\ldots,v_p\}\) telle que tout \(v\in E\) est combinaison linéaire des \(v_i\).
- **Famille libre** : seule combinaison linéaire nulle est la triviale.
- **Base** : famille à la fois libre et génératrice; sa cardinalité est la dimension de \(E\).

## Propriétés fondamentales
- Toute famille génératrice contient une base; toute famille libre se complète en base.
- **Dimension** : si \(E\) est de dimension finie, toutes les bases ont le même cardinal.
- **Formule du rang** : pour une application linéaire \(f : E \to F\), \(\dim \ker f + \dim \operatorname{Im} f = \dim E\).
- **Théorème de la dimension** : pour des SEV \(F,G\subset E\), \(\dim(F+G) = \dim F + \dim G - \dim(F\cap G)\).

## Méthodes de résolution
1. **Tester la stabilité** pour identifier un SEV (vérifier 0, addition, homothétie).
2. **Élimination de Gauss** pour déterminer la liberté/génération et calculer des bases.
3. **Rang d'une matrice** : déterminer \(\dim \operatorname{Im} f\) via les pivots.
4. **Changement de base** : calculer les matrices de passage pour simplifier les calculs.
5. **Projection et somme directe** : caractériser les SEV complémentaires.

## Exemples clés
- \(\mathbb{R}^n\), espaces de polynômes \(\mathbb{R}_n[X]\), espaces de matrices \(\mathcal{M}_{n,p}(\mathbb{R})\).
- Noyau d'une application linéaire : solutions d'un système homogène.
- Lien entre équations différentielles linéaires et EV de solutions.

## Exercices types
- Déterminer une base de l'espace des polynômes de degré \(\leqslant 3\) annulant \(1\) en 0.
- Résoudre \(f(x+y)=f(x)+f(y)\) sur \(\mathbb{R}\) sous hypothèse de continuité et interpréter comme morphisme d'EV.
- Chercher la dimension de \(E = \{(x,y,z) \in \mathbb{R}^3 : x+y+z=0\}\).

## Connexions utiles
- Voir [[Algèbre – Matrices et applications linéaires]] pour les représentations matricielles.
- Voir [[Algèbre – Calcul matriciel et déterminants]] pour les outils de rang.
