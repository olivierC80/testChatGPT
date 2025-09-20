---
tags: [MPSI, Analyse, Fonctions, Exercices]
---

# Exercice – Variations et équation

## Énoncé
On considère la fonction \(f : [0,+\infty[ \to \mathbb{R}\) définie par
\[
f(x) = (x+1)\mathrm{e}^{-x}.
\]
1. Étudier la limite de \(f\) en \(+\infty\) et en 0, puis dresser son tableau de variations.
2. Montrer que l'équation \(f(x) = \tfrac{1}{2}\) admet une unique solution sur \([0,+\infty[\) et fournir un encadrement décimal à \(10^{-2}\) près.

## Correction
1. **Limites et dérivée** : on dispose de \(\lim_{x\to +\infty} (x+1)\mathrm{e}^{-x} = 0\) car l'exponentielle domine toute puissance, tandis que \(f(0) = 1\). Pour \(x>0\), la dérivée vaut
   \[
   f'(x) = \mathrm{e}^{-x} - (x+1)\mathrm{e}^{-x} = -x\, \mathrm{e}^{-x} \leqslant 0.
   \]
   La fonction est donc strictement décroissante sur \([0,+\infty[\). Le tableau de variations fait apparaître une décroissance de 1 vers 0.
2. **Unicité et calcul approché** : la continuité et la stricte décroissance garantissent l'existence d'un unique \(\alpha\in[0,+\infty[\) tel que \(f(\alpha)=\tfrac{1}{2}\). Pour l'estimation, on calcule par exemple \(f(1{,}6)\approx 0{,}54\) et \(f(1{,}7)\approx 0{,}49\) : la solution est donc dans \([1{,}6,1{,}7]\). Un affinage par dichotomie mène à \(\alpha \approx 1{,}68\), précision meilleure que \(10^{-2}\).

**Remarque** : une méthode numérique (dichotomie, méthode de Newton) s'appuie directement sur la monotonie prouvée.
