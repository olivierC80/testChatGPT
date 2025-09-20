---
tags: [MPSI, Analyse, Fonctions, Exercices]
---

# Exercice – Convexité et inégalité

## Énoncé
Soit \(f : (0,+\infty) \to \mathbb{R}\) définie par \(f(x)=\ln x\).
1. Étudier le signe de \(f''(x)\) et en déduire la concavité de \(f\).
2. Montrer que, pour tout \(x>0\), on a \(\ln x \leqslant x-1\) avec égalité seulement en \(x=1\).
3. Interpréter cette inégalité en termes géométriques.

## Correction
1. **Seconde dérivée** : \(f'(x)=1/x\) puis \(f''(x)=-1/x^2 < 0\) sur \((0,+\infty)\). La fonction \(f\) est donc concave.
2. **Inégalité** : la concavité implique que \(f\) est située sous toute tangente. Celle en \(x=1\) vaut \(y = f(1) + f'(1)(x-1) = 0 + 1\cdot(x-1) = x-1\). Pour tout \(x>0\), \(\ln x \leqslant x-1\), l'égalité n'ayant lieu qu'au point de tangence \(x=1\).
3. **Interprétation géométrique** : le graphe de \(y=\ln x\) est situé en dessous de sa tangente en 1. Cette propriété illustre la concavité et fournit une majoration utile pour comparer des croissances logarithmiques et linéaires.

**Remarque** : l'inégalité se réécrit \(x \geqslant \mathrm{e}^{x-1}\) qui intervient fréquemment dans l'étude de limites et dans les preuves d'inégalités intégrales.
