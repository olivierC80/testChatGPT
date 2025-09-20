---
tags: [MPSI, Algèbre, Déterminants]
---

# Algèbre – Calcul matriciel et déterminants

## Définitions essentielles
- **Déterminant** : application \(\det : \mathcal{M}_n(\mathbb{K}) \to \mathbb{K}\) multilinéaire, alternée, normalisée par \(\det I_n = 1\).
- **Cofacteur** : \(C_{ij} = (-1)^{i+j}M_{ij}\) où \(M_{ij}\) est le mineur obtenu en supprimant la ligne \(i\) et la colonne \(j\).
- **Adjugée** : transposée de la matrice des cofacteurs; \(A \cdot \operatorname{Adj}(A) = \det(A) I_n\).

## Propriétés fondamentales
- **Multiplicativité** : \(\det(AB) = \det A \cdot \det B\).
- **Inversibilité** : \(A\) inversible ssi \(\det A \neq 0\).
- **Opérations élémentaires** : échange de deux lignes change le signe du déterminant; ajout d'un multiple d'une ligne n'en change pas la valeur; multiplication d'une ligne par \(\lambda\) multiplie le déterminant par \(\lambda\).
- **Développement de Laplace** : calculer \(\det A\) par expansion le long d'une ligne ou colonne.

## Méthodes de calcul
1. **Triangularisation** : réduire \(A\) en matrice triangulaire supérieure via Gauss; le déterminant est alors le produit diagonal.
2. **Déterminants remarquables** : Vandermonde, circulants, matrices de Cauchy.
3. **Utilisation de symétries** : matrices symétriques, antisymétriques, blocs.
4. **Déterminant d'une application linéaire** : calcul via matrice dans une base orthonormée.
5. **Systèmes de Cramer** : résolution de \(Ax=b\) lorsque \(\det A \neq 0\).

## Exemples clés
- Déterminant de Vandermonde : \(\prod_{i<j} (x_j - x_i)\).
- Calcul de \(\det(I_n + uv^T) = 1 + v^T u\) (formule de Sherman-Morrison).
- Déterminant d'une matrice diagonale par blocs = produit des déterminants des blocs.

## Exercices types
- Calculer \(\det(A)\) pour \(A\) matrice de taille 3 associée à un produit vectoriel.
- Montrer que \(\det(\exp A) = \exp(\operatorname{tr} A)\).
- Résoudre un système par Cramer et interpréter géométriquement.

## Connexions utiles
- Voir [[Algèbre – Matrices et applications linéaires]] pour l'usage des déterminants dans l'inversibilité.
- Voir [[Géométrie – Produit scalaire et orthogonalité]] pour l'interprétation géométrique du déterminant en dimension 3.
