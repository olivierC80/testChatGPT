---
tags: [MPSI, Algèbre, Matrices]
---

# Algèbre – Matrices et applications linéaires

## Définitions essentielles
- **Application linéaire** : \(f : E \to F\) telle que \(f(u+v)=f(u)+f(v)\) et \(f(\lambda u)=\lambda f(u)\).
- **Matrice associée** : représentation de \(f\) dans des bases choisies; notée \(\mathrm{Mat}_{\mathcal{B},\mathcal{C}}(f)\).
- **Composition** : correspond au produit matriciel; identité \(I_n\) est neutre.
- **Inverse** : matrice \(A^{-1}\) telle que \(AA^{-1}=I\).

## Propriétés fondamentales
- **Rang** : dimension de l'image; invariant par changement de base.
- **Noyau** : solutions de \(Ax=0\); dimension liée par \(\dim \ker A = n - \operatorname{rg} A\).
- **Théorème de l'application linéaire** : \(f\) est inversible ssi \(\operatorname{rg} f = \dim E\).
- **Réduction de matrices** : opérations élémentaires ne changent pas le rang mais simplifient la matrice.

## Méthodes usuelles
1. **Pivot de Gauss** : résoudre \(Ax=b\), déterminer \(A^{-1}\) si elle existe.
2. **Calcul de l'image et du noyau** : utiliser un système de générateurs pour la base de l'image.
3. **Composition** : vérifier que \(\mathrm{Mat}(g\circ f)=\mathrm{Mat}(g)\cdot\mathrm{Mat}(f)\).
4. **Matrices particulières** : projecteurs, symétries, endomorphismes diagonalisables.
5. **Exponentielle de matrice** : \(e^A = \sum_{k=0}^{+\infty} \frac{A^k}{k!}\) pour résoudre des systèmes linéaires différentielles.

## Exemples clés
- Matrices triangulaires : déterminant = produit des éléments diagonaux.
- Matrices de passage entre bases canoniques et orthonormales.
- Matrices d'un endomorphisme de projection, rotation, symétrie.

## Exercices types
- Calculer \(A^n\) pour une matrice triangulaire supérieure.
- Déterminer la dimension de \(\operatorname{Im} f\) et \(\ker f\) pour \(f\) définie par \(f(x,y,z) = (x+y, y+z, x+z)\).
- Trouver la matrice de l'application \(f : \mathbb{R}_2[X] \to \mathbb{R}_2[X]\) définie par \(f(P) = P' + P\).

## Connexions utiles
- Voir [[Algèbre – Calcul matriciel et déterminants]] pour les formules de déterminants.
- Voir [[Algèbre – Espaces vectoriels]] pour la notion de base et dimension.
