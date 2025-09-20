---
tags: [MPSI, Analyse, Séries]
---

# Analyse – Séries numériques

## Définitions essentielles
- **Série** : somme formelle \(\sum_{n=0}^{+\infty} u_n\) d'une suite \((u_n)\).
- **Somme partielle** : \(S_n = \sum_{k=0}^n u_k\).
- **Convergence** : la série converge si \((S_n)\) converge vers une limite \(S\).
- **Série à termes positifs** : tous les \(u_n\geqslant 0\); convergence équivalente à la borne supérieure finie des \(S_n\).

## Théorèmes clés
- **Test de Cauchy** : \(\sum u_n\) converge si et seulement si \((S_n)\) est de Cauchy.
- **Critère de comparaison** : si \(0\leqslant u_n\leqslant v_n\) à partir d'un rang et \(\sum v_n\) converge, alors \(\sum u_n\) converge.
- **Critère des séries géométriques** : \(\sum q^n\) converge si \(|q|<1\) avec somme \(\frac{1}{1-q}\).
- **Critère de d'Alembert** : \(\limsup \left|\frac{u_{n+1}}{u_n}\right|<1\) implique la convergence absolue.
- **Critère de Raabe** : si \(n\left(1-\frac{u_{n+1}}{u_n}\right) > 1\) pour \(n\) grand, la série converge.
- **Test de sommation intégrale** : convergence de \(\int_a^{+\infty} f(t)\,\mathrm{d}t\) équivalente à celle de \(\sum f(n)\) pour \(f\) décroissante positive.

## Méthodes d'étude
1. **Absolue vs conditionnelle** : commencer par tester la convergence absolue via \(|u_n|\).
2. **Comparaison** : comparer à une série connue (géométrique, Riemann \(1/n^\alpha\), exponentielle).
3. **Séries alternées** : utiliser le critère spécial (Leibniz) et majorations du reste.
4. **Développement limité** : obtenir l'équivalent de \(u_n\) pour décider de la convergence.
5. **Somme d'une série** : manipuler les sommes partielles, utiliser des séries géométriques ou les séries entières associées.

## Séries classiques
- Série de Riemann : \(\sum \frac{1}{n^\alpha}\) converge ssi \(\alpha>1\).
- Série harmonique alternée : \(\sum (-1)^n \frac{1}{n}\) converge conditionnellement vers \(\ln 2\).
- Série exponentielle : \(\sum \frac{x^n}{n!} = e^x\).
- Série logarithmique : \(\sum \frac{x^n}{n} = -\ln(1-x)\) pour \(|x|<1\).

## Exercices types
- Étudier la convergence et sommer \(\sum \frac{(-1)^n}{n(n+1)}\) → voir [[Exercice - Séries numériques - Série alternée télescopique]].
- Comparer \(\sum \frac{\sqrt{n}}{n^2+1}\) à \(\sum \frac{1}{n^{3/2}}\) → voir [[Exercice - Séries numériques - Comparaison asymptotique]].
- Utiliser un DL pour décider de la convergence de \(\sum \left(\sqrt{n+1}-\sqrt{n}\right)\) → voir [[Exercice - Séries numériques - DL et convergence]].
- Déterminer un équivalent du reste \(R_n = \sum_{k=n+1}^{+\infty} u_k\) → voir [[Exercice - Séries numériques - Estimation du reste]].


## Connexions utiles
- Voir [[Analyse – Suites et limites]] pour les techniques d'équivalents.
- Voir [[Analyse – Équations différentielles linéaires]] pour les séries génératrices.
