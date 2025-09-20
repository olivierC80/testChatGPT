---
tags: [MPSI, Analyse, Fonctions]
---

# Analyse – Fonctions d'une variable réelle

## Définitions essentielles
- **Limite en un point** : \(\lim_{x\to a} f(x)=\ell\) signifie \(\forall \varepsilon>0,\ \exists \eta>0 : 0<|x-a|<\eta \Rightarrow |f(x)-\ell|<\varepsilon\).
- **Continuité** : \(f\) est continue en \(a\) si \(\lim_{x\to a} f(x) = f(a)\).
- **Dérivabilité** : \(f\) est dérivable en \(a\) si \(\lim_{h\to0} \frac{f(a+h)-f(a)}{h}\) existe; notée \(f'(a)\).
- **Classe \(\mathcal{C}^k\)** : \(f\) admet des dérivées continues jusqu'à l'ordre \(k\).

## Théorèmes clés
- **Théorème des valeurs intermédiaires (TVI)** : pour \(f\) continue sur \([a,b]\), toute valeur intermédiaire est atteinte.
- **Théorème de Rolle** et **des accroissements finis** : fournit \(c\in(a,b)\) tel que \(f'(c)=0\) ou \(f'(c)=\frac{f(b)-f(a)}{b-a}\).
- **Formule de Taylor avec reste** : \(f(x)=\sum_{k=0}^n \frac{f^{(k)}(a)}{k!}(x-a)^k + R_n(x)\) avec estimation du reste (Lagrange, intégral).
- **Théorème de continuité des fonctions monotones** : une fonction monotone sur un intervalle est continue sauf en un nombre au plus dénombrable de points.
- **Réciproque locale** : si \(f\) est \(\mathcal{C}^1\), strictement monotone et \(f'(a)\neq 0\), alors \(f\) admet une réciproque \(\mathcal{C}^1\) près de \(a\).

## Méthodes d'étude
1. **Tableaux de variation** : dériver, étudier le signe de \(f'\) et synthétiser les comportements.
2. **Développements limités (DL)** : calculer un DL autour d'un point pour obtenir limites, équivalents et tangentes.
3. **Comparaison aux fonctions usuelles** : exponentielle, logarithme, trigonométriques.
4. **Étude de la convexité** : analyser \(f''\) ou les variations de \(f'\) pour déduire points d'inflexion et inégalités (Jensen, inégalité des accroissements finis).
5. **Changements de variable** : substitution, composition, symétries pour simplifier calculs.

## Exemples incontournables
- Fonctions polynomiales, rationnelles, exponentielles, logarithmes, trigonométriques et compositions.
- Fonction \(x \mapsto x^x\) pour l'étude des limites via \(\ln\).
- Fonction \(x \mapsto \frac{\sin x}{x}\) et ses limites ainsi que son DL.
- Étude des équations transcendantes \(\ln x = x-2\), \(\cos x = x\).

## Exercices types

- Étudier les variations de \(f(x) = (x+1)\mathrm{e}^{-x}\) et résoudre \(f(x)=\tfrac{1}{2}\) → voir [[Exercice - Fonctions d'une variable réelle - Variations et équation]].
- Calculer la limite \(\lim_{x\to0} \frac{\ln(1+x)-x+\tfrac{x^2}{2}}{x^3}\) à l'aide d'un DL → voir [[Exercice - Fonctions d'une variable réelle - DL et équivalent]].
- Étudier la continuité et la dérivabilité en 0 de \(h(x)=x^2\sin(1/x)\) pour \(x\neq 0\) → voir [[Exercice - Fonctions d'une variable réelle - Dérivabilité par morceaux]].
- Exploiter la concavité de \(\ln x\) sur \((0,+\infty)\) pour établir \(\ln x \leqslant x-1\) → voir [[Exercice - Fonctions d'une variable réelle - Convexité et inégalité]].


## Connexions utiles
- Voir [[Analyse – Suites et limites]] pour la comparaison par suites extraites.
- Voir [[Analyse – Intégration sur un segment]] pour les primitives et l'étude des variations par intégrale.
