---
tags: [MPSI, Probabilités, Variables aléatoires]
---

# Probabilités – Variables aléatoires discrètes

## Définitions essentielles
- **Variable aléatoire discrète (VAD)** : application \(X : \Omega \to \mathbb{R}\) prenant un nombre fini ou dénombrable de valeurs.
- **Loi de probabilité** : \(p_X(x_i) = \mathbb{P}(X=x_i)\) avec \(\sum_i p_X(x_i) = 1\).
- **Fonction de répartition** : \(F_X(t) = \mathbb{P}(X\leqslant t)\).
- **Espérance** : \(\mathbb{E}(X) = \sum_i x_i p_X(x_i)\); **variance** \(\operatorname{Var}(X) = \mathbb{E}(X^2) - \mathbb{E}(X)^2\).

## Lois classiques
- **Bernoulli** \(\mathcal{B}(p)\) : \(\mathbb{P}(X=1)=p\), \(\mathbb{P}(X=0)=1-p\).
- **Binomiale** \(\mathcal{B}(n,p)\) : somme de \(n\) Bernoulli indépendantes.
- **Géométrique** \(\mathcal{G}(p)\) : nombre d'essais avant le premier succès.
- **Poisson** \(\mathcal{P}(\lambda)\) : modèle pour les événements rares; \(\mathbb{P}(X=k)=e^{-\lambda}\frac{\lambda^k}{k!}\).

## Théorèmes et propriétés
- **Linéarité de l'espérance** : \(\mathbb{E}(aX+bY) = a\mathbb{E}(X) + b\mathbb{E}(Y)\).
- **Variance d'une somme** : si \(X,Y\) indépendantes, \(\operatorname{Var}(X+Y) = \operatorname{Var}(X)+\operatorname{Var}(Y)\).
- **Inégalité de Bienaymé-Tchebychev** : \(\mathbb{P}(|X-\mathbb{E}(X)| \geqslant \varepsilon) \leqslant \frac{\operatorname{Var}(X)}{\varepsilon^2}\).
- **Approximation de Poisson** : pour \(n\) grand, \(\mathcal{B}(n,p)\) s'approxime par \(\mathcal{P}(\lambda)\) avec \(\lambda = np\).

## Méthodes de calcul
1. **Tableaux de probabilités** : dresser les valeurs et probabilités pour éviter les oublis.
2. **Utilisation des génératrices** : fonction \(G_X(t) = \mathbb{E}(t^X)\) pour sommer ou calculer espérances.
3. **Conditionnement** : \(\mathbb{P}(A) = \sum_i \mathbb{P}(A|X=x_i) p_X(x_i)\).
4. **Indépendance** : vérifier \(\mathbb{P}(X=x, Y=y) = \mathbb{P}(X=x)\mathbb{P}(Y=y)\).
5. **Formule des probabilités totales** et **de Bayes** pour réviser les probabilités conditionnelles.

## Exercices types
- Calculer \(\mathbb{E}(X)\) et \(\operatorname{Var}(X)\) pour \(X\sim\mathcal{B}(n,p)\).
- Étudier la loi du maximum de deux variables indépendantes discrètes.
- Résoudre un problème d'arrêt optimal simple (jeu à somme finie).
- Approcher la loi binomiale par une loi de Poisson dans un problème de files d'attente.

## Connexions utiles
- Voir [[Algèbre – Espaces vectoriels]] pour l'interprétation de l'espérance comme produit scalaire.
- Voir [[Analyse – Séries numériques]] pour la convergence des séries de probabilités.
