---
tags: [MPSI, Analyse, Séries, Exercices]
---

# Exercice – Estimation du reste

## Énoncé
Pour la série convergente de Riemann \(\sum_{k=1}^{+\infty} \frac{1}{k^2}\), déterminer un équivalent du reste
\[
R_n = \sum_{k=n+1}^{+\infty} \frac{1}{k^2}
\]
quand \(n \to +\infty\).

## Correction
1. **Encadrement intégral** : la fonction \(f(x) = \frac{1}{x^2}\) est décroissante sur \([1,+\infty[\). On dispose des encadrements classiques
   \[
   \int_{n+1}^{+\infty} f(x)\,\mathrm{d}x \leqslant R_n \leqslant \int_{n}^{+\infty} f(x)\,\mathrm{d}x.
   \]
2. **Calcul des intégrales** : on obtient
   \[
   \int_{n}^{+\infty} \frac{\mathrm{d}x}{x^2} = \frac{1}{n} \quad\text{et}\quad \int_{n+1}^{+\infty} \frac{\mathrm{d}x}{x^2} = \frac{1}{n+1}.
   \]
   Ainsi,
   \[
   \frac{1}{n+1} \leqslant R_n \leqslant \frac{1}{n}.
   \]
3. **Équivalent** : comme \(\frac{1}{n+1} \sim \frac{1}{n}\), on en déduit que \(R_n \sim \frac{1}{n}\).

**Conclusion** : le reste de la série de Riemann d'ordre 2 est équivalent à \(\frac{1}{n}\).
