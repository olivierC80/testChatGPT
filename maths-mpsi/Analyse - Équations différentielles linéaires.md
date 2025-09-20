---
tags: [MPSI, Analyse, Équations différentielles]
---

# Analyse – Équations différentielles linéaires

## Définitions essentielles
- **Équation différentielle linéaire d'ordre 1** : \(y' + a(x)y = b(x)\) sur un intervalle \(I\).
- **Équation homogène associée** : \(y' + a(x)y = 0\) ; ses solutions forment un espace vectoriel de dimension 1.
- **Équation d'ordre 2 à coefficients constants** : \(y'' + ay' + by = c(x)\) avec \(a,b\in\mathbb{R}\).

## Théorèmes clés
- **Existence et unicité** : pour \(a,b\) continues, il existe une unique solution passant par \((x_0, y_0)\).
- **Méthode de variation de la constante** : solution générale de \(y' + a(x)y = b(x)\) : \(y(x) = e^{-A(x)}\left(\int e^{A(x)}b(x)\,dx + C\right)\) où \(A'(x)=a(x)\).
- **Superposition** : pour une équation linéaire, la somme de solutions particulières est solution si elles sont associées à des second membres s'additionnant.
- **Résolution d'ordre 2** : utiliser l'équation caractéristique \(r^2 + ar + b = 0\) et traiter les cas racines simples, doubles, complexes.

## Méthodes usuelles
1. **Facteur intégrant** : pour l'ordre 1, multiplier par \(\mu(x)=e^{\int a(x)dx}\).
2. **Recherche d'une solution particulière** : coefficients indéterminés pour second membre polynomial, exponentiel ou trigonométrique.
3. **Réduction du second ordre à un système** : introduire \(X = (y, y')\) et utiliser les matrices exponentielles.
4. **Utilisation des conditions initiales** : résoudre les constantes en imposant \(y(x_0)=y_0\), \(y'(x_0)=y_1\).
5. **Stabilité** : étudier le signe des parties réelles des racines caractéristiques.

## Exemples classiques
- \(y' - y = e^x\) : solution générale \(y(x) = Ce^{x} + \frac{1}{2} e^{x}(x-1)\).
- Oscillateur harmonique \(y'' + \omega^2 y = 0\) : solutions \(A\cos \omega x + B\sin \omega x\).
- Circuit RLC : \(L y'' + R y' + \frac{1}{C} y = E(t)\).

## Exercices types
- Résoudre \(y'' - 3y' + 2y = e^{2x}\) en déterminant la solution particulière.
- Étudier le comportement asymptotique des solutions de \(y' + \frac{1}{x}y = \frac{1}{x^2}\) sur \((0,+\infty)\).
- Vérifier l'indépendance linéaire de solutions via le wronskien.

## Connexions utiles
- Voir [[Algèbre – Matrices et applications linéaires]] pour l'exponentielle de matrice.
- Voir [[Analyse – Séries numériques]] pour la résolution via séries formelles.
