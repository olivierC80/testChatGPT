---
tags: [MPSI, Analyse, Séries, Exercices]
---

# Exercice – Comparaison asymptotique

## Énoncé
Étudier la convergence de la série à termes positifs \(\sum_{n=1}^{+\infty} \frac{\sqrt{n}}{n^2+1}\) en la comparant à une série de référence.

## Correction
1. **Équivalent du terme général** : pour \(n\to +\infty\), on a
   \[
   \frac{\sqrt{n}}{n^2+1} = \frac{\sqrt{n}}{n^2\left(1+\frac{1}{n^2}\right)} = \frac{1}{n^{3/2}} \cdot \frac{1}{1+\frac{1}{n^2}} \sim \frac{1}{n^{3/2}}.
   \]
2. **Série de comparaison** : la série de Riemann \(\sum \frac{1}{n^{3/2}}\) converge car \(\frac{3}{2} > 1\).
3. **Conclusion** : les termes de la série proposée sont équivalents à ceux d'une série convergente à partir d'un certain rang. Le critère d'équivalence implique que \(\sum_{n=1}^{+\infty} \frac{\sqrt{n}}{n^2+1}\) converge.

**Remarque** : on peut également utiliser une comparaison directe en majorant \(\frac{\sqrt{n}}{n^2+1} \leqslant \frac{\sqrt{n}}{n^2} = \frac{1}{n^{3/2}}\) pour \(n \geqslant 1\).
