---
tags: [MPSI, Géométrie, Produit scalaire]
---

# Géométrie – Produit scalaire et orthogonalité

## Définitions essentielles
- **Produit scalaire** : application symétrique bilinéaire \(\langle u,v\rangle\) définie positive sur un EV réel.
- **Norme** : \(\|v\| = \sqrt{\langle v,v\rangle}\).
- **Vecteurs orthogonaux** : \(\langle u,v\rangle = 0\).
- **Base orthonormée (ON)** : base \((e_i)\) telle que \(\langle e_i,e_j\rangle = \delta_{ij}\).

## Théorèmes clés
- **Inégalité de Cauchy-Schwarz** : \(|\langle u,v\rangle| \leqslant \|u\|\,\|v\|\).
- **Identité du parallélogramme** : \(\|u+v\|^2 + \|u-v\|^2 = 2(\|u\|^2 + \|v\|^2)\).
- **Projection orthogonale** : sur un SEV \(F\) de dimension finie, il existe une unique projection orthogonale.
- **Théorème de Pythagore** : si \(u\perp v\), alors \(\|u+v\|^2 = \|u\|^2 + \|v\|^2\).
- **Processus de Gram-Schmidt** : permet d'orthonormaliser une base.

## Méthodes usuelles
1. **Calcul d'une projection** : \(\operatorname{proj}_F(u) = \sum \frac{\langle u,e_i\rangle}{\|e_i\|^2} e_i\) dans une base orthonormée \((e_i)\).
2. **Décomposition orthogonale** : \(u = \operatorname{proj}_F(u) + \operatorname{proj}_{F^{\perp}}(u)\).
3. **Angles et distances** : \(\cos \theta = \frac{\langle u,v\rangle}{\|u\|\,\|v\|}\).
4. **Utilisation du produit vectoriel en dimension 3** : pour calculer une normale ou une aire orientée.
5. **Matrice de Gram** : \(G = (\langle v_i,v_j\rangle)\) pour tester l'orthogonalité ou calculer des volumes.

## Exemples clés
- Calcul de distances point-plan, point-droite dans \(\mathbb{R}^3\).
- Orthogonalisation d'une base \((1,x,x^2)\) dans \(\mathbb{R}_2[X]\) avec le produit scalaire \(\langle P,Q\rangle = \int_0^1 P(t)Q(t)\,dt\).
- Recherche de la sphère inscrite à un tétraèdre via projections.

## Exercices types
- Déterminer la projection orthogonale d'un vecteur sur un plan donné par deux vecteurs directeurs.
- Construire une base orthonormée à partir de vecteurs \(u,v,w\) libres dans \(\mathbb{R}^3\).
- Montrer que deux plans sont orthogonaux en utilisant leurs vecteurs normaux.

## Connexions utiles
- Voir [[Algèbre – Calcul matriciel et déterminants]] pour l'aire/parallélépipède mixte.
- Voir [[Probabilités – Variables aléatoires discrètes]] pour l'analogie avec l'orthogonalité des fonctions indicatrices.
