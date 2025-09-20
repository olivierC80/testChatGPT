---
tags: [MPSI, Analyse, Fonctions, Exercices]
---

# Exercice – Dérivabilité par morceaux

## Énoncé
On considère la fonction \(h : \mathbb{R} \to \mathbb{R}\) définie par
\[
h(x) = \begin{cases}
 x^2 \sin\left(\dfrac{1}{x}\right) & \text{si } x \neq 0, \\
 0 & \text{si } x = 0.
\end{cases}
\]
1. Étudier la continuité de \(h\) en 0.
2. Montrer que \(h\) est dérivable en 0 et déterminer \(h'(0)\).
3. Donner l'expression de \(h'(x)\) pour \(x\neq 0\) et discuter l'existence de \(h'\) en 0.

## Correction
1. **Continuité en 0** : pour \(x\neq 0\), \(|h(x)| \leqslant x^2\) car \(|\sin(1/x)| \leqslant 1\). Par conséquent, \(\lim_{x\to 0} h(x) = 0 = h(0)\); la fonction est continue en 0.
2. **Dérivabilité** : le taux d'accroissement vaut
   \[
   \frac{h(x)-h(0)}{x} = x \sin\left(\frac{1}{x}\right).
   \]
   Cette expression est bornée par \(|x|\), donc tend vers 0 lorsque \(x\to 0\). On en déduit que \(h\) est dérivable en 0 et \(h'(0)=0\).
3. **Dérivée hors de 0 et discussion** : pour \(x\neq 0\), on dérive comme une composition et obtient
   \[
   h'(x) = 2x \sin\left(\frac{1}{x}\right) - \cos\left(\frac{1}{x}\right).
   \]
   La dérivée existe donc partout, et \(h'\) n'est pas continue en 0 car le terme \(-\cos(1/x)\) n'admet pas de limite quand \(x\to 0\), bien que \(h'(0)=0\).

**Remarque** : cet exemple illustre une fonction \(\mathcal{C}^1\) sur \(\mathbb{R}\\setminus\{0\}\) prolongeable en une fonction dérivable en 0 mais dont la dérivée n'est pas continue en 0.
