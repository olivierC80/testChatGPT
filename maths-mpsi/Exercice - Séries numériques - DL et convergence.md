---
tags: [MPSI, Analyse, Séries, Exercices]
---

# Exercice – Développement limité et convergence

## Énoncé
Déterminer la nature de la série \(\sum_{n=1}^{+\infty} \left(\sqrt{n+1}-\sqrt{n}\right)\) à l'aide d'un développement limité.

## Correction
1. **Développement limité** : pour \(x > 0\), on dispose du DL \(\sqrt{1+x} = 1 + \frac{x}{2} - \frac{x^2}{8} + O(x^3)\). En posant \(x = \frac{1}{n}\), on obtient
   \[
   \sqrt{n+1} = \sqrt{n}\,\sqrt{1+\frac{1}{n}} = \sqrt{n}\left(1 + \frac{1}{2n} - \frac{1}{8n^2} + O\left(\frac{1}{n^3}\right)\right).
   \]
   Ainsi
   \[
   \sqrt{n+1} - \sqrt{n} = \sqrt{n}\left(\frac{1}{2n} - \frac{1}{8n^2} + O\left(\frac{1}{n^3}\right)\right) = \frac{1}{2\sqrt{n}} + O\left(\frac{1}{n^{3/2}}\right).
   \]
2. **Comparaison** : les termes de la série sont équivalents à \(\frac{1}{2\sqrt{n}}\).
3. **Nature de la série** : la série de Riemann \(\sum \frac{1}{\sqrt{n}}\) diverge (exposant \(\frac{1}{2} \leqslant 1\)). Le critère d'équivalence montre donc que la série étudiée diverge également.

**Conclusion** : la série \(\sum \left(\sqrt{n+1}-\sqrt{n}\right)\) diverge.
