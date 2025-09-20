---
tags: [MPSI, Analyse, Fonctions, Exercices]
---

# Exercice – Développement limité et équivalent

## Énoncé
Déterminer la limite de la fonction
\[
\varphi(x) = \frac{\ln(1+x) - x + \tfrac{x^2}{2}}{x^3}
\]
quand \(x\to 0\). On précisera un équivalent du numérateur.

## Correction
1. **Développement limité** : au voisinage de 0, on a le DL d'ordre 3
   \[
   \ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} + o(x^3).
   \]
   D'où
   \[
   \ln(1+x) - x + \tfrac{x^2}{2} = \frac{x^3}{3} + o(x^3).
   \]
2. **Limite** : on en déduit \(\varphi(x) = \frac{\frac{x^3}{3} + o(x^3)}{x^3} = \frac{1}{3} + o(1)\). Ainsi, \(\lim_{x\to 0} \varphi(x) = \tfrac{1}{3}\).

**Remarque** : on pouvait aussi considérer la fonction \(x\mapsto \ln(1+x) - x + \tfrac{x^2}{2}\) et appliquer la règle de l'Hôpital trois fois, mais l'approche par DL est plus rapide et standard en MPSI.
