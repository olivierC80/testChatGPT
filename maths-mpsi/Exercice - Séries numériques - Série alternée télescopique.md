---
tags: [MPSI, Analyse, Séries, Exercices]
---

# Exercice – Série alternée télescopique

## Énoncé
Étudier la convergence de la série \(\sum_{n=1}^{+\infty} \frac{(-1)^n}{n(n+1)}\) et calculer sa somme lorsqu'elle converge.

## Correction
1. **Convergence** : la suite \(u_n = \frac{(-1)^n}{n(n+1)}\) est alternée et \(|u_n| = \frac{1}{n(n+1)}\) est décroissante vers 0. Le critère de Leibniz garantit donc la convergence.
2. **Décomposition en somme télescopique** :
   \[
   \frac{(-1)^n}{n(n+1)} = (-1)^n\left(\frac{1}{n} - \frac{1}{n+1}\right).
   \]
   On obtient ainsi
   \[
   \sum_{n=1}^{N} \frac{(-1)^n}{n(n+1)} = \sum_{n=1}^{N} \frac{(-1)^n}{n} - \sum_{n=1}^{N} \frac{(-1)^n}{n+1}.
   \]
3. **Limite des sommes partielles** : en décalant l'indice dans la seconde somme, on trouve
   \[
   \sum_{n=1}^{N} \frac{(-1)^n}{n(n+1)} = \sum_{n=1}^{N} \frac{(-1)^n}{n} + \sum_{n=2}^{N+1} \frac{(-1)^n}{n} = -\ln 2 + \left(-\ln 2 + 1\right) + o(1).
   \]
   Par passage à la limite quand \(N\to +\infty\), la somme vaut donc \(1 - 2\ln 2\).

**Conclusion** : la série converge et sa somme est \(1 - 2\ln 2\).
