---
tags: [MPSI, Analyse, Suites]
---

# Analyse – Suites et limites

## Définitions essentielles
- **Suite réelle** : application \(u : \mathbb{N} \to \mathbb{R}\), notée \((u_n)_{n\geqslant0}\).
- **Suite convergente** : il existe \(\ell \in \mathbb{R}\) tel que \(\forall \varepsilon>0,\ \exists N:\ n\geqslant N \Rightarrow |u_n-\ell|<\varepsilon\).
- **Suite divergente vers \(+\infty\)** : \(\forall A\in\mathbb{R},\ \exists N:\ n\geqslant N \Rightarrow u_n>A\).
- **Suite monotone** : \((u_n)\) croissante si \(u_{n+1}\geqslant u_n\); décroissante si \(u_{n+1}\leqslant u_n\).

## Théorèmes clés
- **Théorème de convergence monotone** : toute suite réelle monotone et majorée (resp. minorée) converge.
- **Théorème des gendarmes** : si \(u_n \leqslant v_n \leqslant w_n\) et \(u_n\to \ell, w_n\to \ell\), alors \(v_n\to \ell\).
- **Suites adjacentes** : si \((u_n)\) croissante, \((v_n)\) décroissante, \(u_n\leqslant v_n\) et \(v_n-u_n\to0\), alors \((u_n)\) et \((v_n)\) convergent vers la même limite.
- **Théorème de Bolzano-Weierstrass** : toute suite bornée de \(\mathbb{R}\) admet une sous-suite convergente.
- **Formule de Stolz** (cas sommatoire) : pour des suites réelles \((u_n)\) et \((v_n)\) avec \(v_n\) strictement croissante et \(v_n\to +\infty\), si la limite de \(\frac{u_{n+1}-u_n}{v_{n+1}-v_n}\) existe et vaut \(L\), alors \(\frac{u_n}{v_n}\to L\).

## Méthodes d'étude
1. **Encadrement** : trouver deux suites simples encadrant \((u_n)\) pour utiliser les gendarmes ou les suites adjacentes.
2. **Monotonie et bornes** : démontrer la croissance/décroissance et une majoration/minoration.
3. **Equivalent & croissance comparée** : utiliser les développements limités ou logarithmes pour comparer.
4. **Transformation** : travailler sur \((u_{n+1}-u_n)\), \((\ln u_n)\) ou sur une relation de récurrence.
5. **Récurrence pour la convergence** : prouver que \(|u_{n+1}-\ell|\leqslant q|u_n-\ell|\) avec \(|q|<1\).

## Exemples importants
- \(u_{n+1}=\frac{1}{2}(u_n+\frac{a}{u_n})\) avec \(u_0>0\) converge vers \(\sqrt{a}\).
- \(u_n = \left(1+\frac{x}{n}\right)^n\to e^x\).
- \(u_n=\sum_{k=1}^n \frac{1}{k}\) diverge mais \(u_n-\ln n\to \gamma\) (constante d'Euler-Mascheroni).
- Suites définies par \(u_{n+1}=\cos u_n\) convergent vers l'unique solution de \(x=\cos x\).

## Exercices types
- Étudier \((u_n)\) définie par récurrence \(u_{n+1}=f(u_n)\) avec \(f\) croissante ou décroissante.
- Déterminer la limite de suites produits ou puissances \(a_n^{1/n}\), \(n^{1/n}\), etc.
- Comparer \(\sum_{k=1}^n \frac{1}{k^\alpha}\) à une intégrale pour obtenir l'équivalent.
- Étudier la convergence d'une suite définie par \(u_n = \frac{1}{n} \sum_{k=1}^n k^p\).

## Connexions utiles
- Voir [[Analyse – Séries numériques]] pour prolonger l'étude des sommes infinies.
- Voir [[Analyse – Fonctions d'une variable réelle]] pour les méthodes de limites de fonctions.
