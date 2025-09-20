---
tags: [MPSI, Analyse, Intégrales]
---

# Analyse – Intégration sur un segment

## Définitions essentielles
- **Fonction intégrable** : fonction continue par morceaux sur \([a,b]\), dont l'intégrale de Riemann existe.
- **Primitive** : \(F\) est une primitive de \(f\) sur \([a,b]\) si \(F' = f\) et \(F\) est \(\mathcal{C}^1\).
- **Intégrale définie** : \(\int_a^b f(x)\,\mathrm{d}x = F(b)-F(a)\) pour une primitive \(F\) de \(f\).

## Théorèmes clés
- **Linéarité et additivité** : \(\int_a^b (\alpha f + \beta g) = \alpha \int_a^b f + \beta \int_a^b g\) et \(\int_a^b f = \int_a^c f + \int_c^b f\).
- **Inégalité de la moyenne** : \(m(b-a) \leqslant \int_a^b f \leqslant M(b-a)\) si \(m\leqslant f \leqslant M\).
- **Théorème fondamental de l'analyse** : si \(F(x) = \int_a^x f(t)\,dt\), alors \(F\) est \(\mathcal{C}^1\) et \(F'=f\).
- **Changement de variable** : \(\int_a^b f(u(x))u'(x)\,dx = \int_{u(a)}^{u(b)} f(t)\,dt\).
- **Intégration par parties** : \(\int_a^b u'(x)v(x)\,dx = [u(x)v(x)]_a^b - \int_a^b u(x)v'(x)\,dx\).

## Méthodes d'intégration
1. **Recherche d'une primitive** : identifier des fonctions usuelles (polynômes, exponentielle, trigonométriques, rationnelles).
2. **IPP** : choisir judicieusement \(u\) et \(v'\) pour simplifier l'intégrale.
3. **Changements de variable** : trigonométriques, exponentiels, substitution affine pour réduire à une forme simple.
4. **Comparaison** : majorer/minorer l'intégrale pour obtenir des encadrements ou limites.
5. **Utilisation des symétries** : intégrales sur \([-a,a]\) avec fonctions paires/impaires.

## Exemples importants
- Calculs de moments \(\int_a^b x^n\,dx\), intégrales trigonométriques \(\int \sin^n x\,dx\), \(\int e^{ax}\cos bx\,dx\).
- Intégrales de fonctions définies par morceaux et notion d'aire.
- Intégrales dépendant d'un paramètre \(I(t)=\int_a^b f(x,t)\,dx\) : continuité, dérivation sous le signe intégral.

## Exercices types
- Déterminer \(\int_0^1 \ln(1+x)\,dx\) via IPP.
- Étudier la fonction \(I(a)=\int_0^1 \frac{x^a-1}{\ln x}\,dx\) et montrer sa continuité.
- Comparer \(\int_0^1 \frac{dx}{\sqrt{x}}\) et \(\int_0^1 \frac{dx}{x}\) (divergence au bord).
- Calculer la valeur moyenne \(\frac{1}{b-a}\int_a^b f\) et l'interpréter géométriquement.

## Connexions utiles
- Voir [[Analyse – Fonctions d'une variable réelle]] pour les primitives et DL.
- Voir [[Analyse – Séries numériques]] pour l'échange somme-intégrale.
